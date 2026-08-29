# Morning email — HTML template

Reference-only. The daily routine reads `output/daily-recap.md` for content and
formats it into this HTML shape before sending to pazanpir350@gmail.com.

---

```html
<div style="font-family: -apple-system, Segoe UI, Roboto, sans-serif; max-width: 520px; margin: 0 auto; color: #1a1a1a; background: #f7f5f2; padding: 24px; border-radius: 12px;">

  <div style="background: linear-gradient(135deg, #4338ca, #7c3aed); border-radius: 10px; padding: 18px 20px; margin-bottom: 20px;">
    <h2 style="margin: 0; color: #ffffff; font-size: 20px;">English recap — {{DATE}}</h2>
    <p style="color: #e0d9ff; margin: 4px 0 0; font-size: 13px;">From yesterday's session</p>
  </div>

  <div style="background: #fff1f0; border-left: 4px solid #dc2626; border-radius: 8px; padding: 14px 18px; margin-bottom: 16px;">
    <h3 style="margin: 0 0 10px; color: #b91c1c; font-size: 15px;">🎯 Mistakes to remember</h3>
    <ul style="margin: 0; padding-left: 20px; color: #3a2323;">
      {{#each mistakes}}
      <li style="margin-bottom: 8px; line-height: 1.4;">{{this}}</li>
      {{/each}}
    </ul>
  </div>

  <div style="background: #ecfdf3; border-left: 4px solid #16a34a; border-radius: 8px; padding: 14px 18px; margin-bottom: 16px;">
    <h3 style="margin: 0 0 10px; color: #15803d; font-size: 15px;">💬 Words &amp; phrases learned</h3>
    <ul style="margin: 0; padding-left: 20px; color: #1e3a2b;">
      {{#each phrases}}
      <li style="margin-bottom: 8px; line-height: 1.4;"><strong style="color: #166534;">{{name}}</strong> — {{meaning}}</li>
      {{/each}}
    </ul>
  </div>

  <div style="background: #fffbeb; border-left: 4px solid #d97706; border-radius: 8px; padding: 14px 18px; font-size: 14px; color: #78350f; line-height: 1.5;">
    {{ONE_LINE}}
  </div>

</div>
```

## Fill-in rules

- `{{DATE}}` — the date from `output/daily-recap.md`
- `{{#each mistakes}}` — one `<li>` per line under "Mistakes to remember" in `daily-recap.md`
- `{{#each phrases}}` — one `<li>` per line under "Words/phrases learned," bold the chunk, meaning after the dash
- `{{ONE_LINE}}` — the "One line" summary in `daily-recap.md`, verbatim, no softening
- If `daily-recap.md` is stale (no session yesterday), say so plainly instead of repeating an old date — don't silently resend the last recap as if it were new.
