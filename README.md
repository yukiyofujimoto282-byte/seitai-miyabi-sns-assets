# SEITAI MIYABI Malaysia — SNS Post Assets

Public image hosting for the SEITAI MIYABI Malaysia organic SNS posting automation.

Instagram/Facebook's Content Publishing API requires images to be fetchable from a
public URL — this repo exists only to satisfy that requirement. It contains nothing
but exported carousel images, organized by post date.

Managed automatically by a scheduled Claude Code routine. See the main ops repo
(`seitai-miyabi-ops`, private) for the actual posting logic and content calendar.

## Structure

```
images/<YYYY-MM-DD>/slide-1.png
images/<YYYY-MM-DD>/slide-2.png
images/<YYYY-MM-DD>/slide-3.png
images/<YYYY-MM-DD>/slide-4.png
```

Raw URL pattern: `https://raw.githubusercontent.com/yukiyofujimoto282-byte/seitai-miyabi-sns-assets/main/images/<date>/slide-N.png`
