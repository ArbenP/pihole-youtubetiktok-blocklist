# Pi-hole YouTube and TikTok Blocklist

A curated blocklist designed to block common YouTube and TikTok domains on Pi-hole. This list helps limit access to these platforms for network management or parental control purposes.

## Features
- Blocks common YouTube domains.
- Blocks common TikTok domains.
- Easy integration with Pi-hole.

## Installation and Usage
To use this blocklist with your Pi-hole, follow these steps:

1. Open your Pi-hole Admin Console.
2. Navigate to **Group Management** > **Adlists**.
3. Add the following URL to the **Address** field:
   ```
   https://github.com/ArbenP/pihole-youtubetiktok-blocklist/blob/main/blocklist.txt
   ```
4. Click **Add**.
5. Update your Pi-hole gravity by running:
   ```bash
   pihole -g
   ```

## Updates
The blocklist is regularly updated to include new domains. To keep your Pi-hole updated with the latest list, ensure you periodically run:
```bash
pihole -g
```

## Contribution
Contributions are welcome! If you notice a domain that's missing or find any issues, feel free to open an issue or submit a pull request.
