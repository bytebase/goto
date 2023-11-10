# Goto: Your Shortcut to the Web
Goto, a lightweight tool with fewer than 200 lines of code, operates as a serverless solution for short links, catering to personal, team, and enterprise needs. Link management is facilitated through GitOps.

The code is primarily generated by GPT with minimal style adjustments by human. The concept and architecture, however, originate from human ingenuity.

## Instruction
The link configuration files can be placed anywhere accessible via URL from the browser. An illustrative configuration is available at `https://github.com/bytebase/goto/raw/main/data.json`. These configurations can be stored in public or private repositories, or essentially in any location.

## Architecture
1. Users define the URLs for configuration files.
1. Chrome extensions read the configurations to map short URLs.
1. When users enter the short URL, the extension redirects them to the full URL.

## Development
1. Go to `chrome://extensions/`.
1. Turn on `Developer mode`.
1. Load unpack of this package.
1. Inspection.
   1. Go to `chrome://inspect/#service-workers`.
   1. Right click `Inspect Popup` on the extension.
