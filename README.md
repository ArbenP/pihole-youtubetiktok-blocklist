# Pi-hole YouTube and TikTok Blocklist

This curated blocklist was developed as part of a project for a client requiring network-level restrictions on YouTube and TikTok. It is designed for use with Pi-hole to help enforce content filtering policies for network management or parental control purposes.

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

## Client-Specific Customisation

This blocklist was tailored to meet a client’s specific content filtering requirements. If you need a customised solution for your network, feel free to reach out at https://noduscloud.com

## Contribution

Community contributions are welcome! If you identify missing domains or issues, feel free to open an issue or submit a pull request.
