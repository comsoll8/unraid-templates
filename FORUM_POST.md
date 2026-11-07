**Title:** [Support] VYZN: self-hosted media server + Android TV app

**Overview**
VYZN scans your Movies/TV folders, matches them with TMDB metadata (Show > Season > Episode), and streams them over HLS to a browser or the Android TV / Google TV app (also runs on a phone). Profiles with content-rating limits, Continue Watching, genre shelves, optional Intel QuickSync (VAAPI) transcoding, optional Seerr integration and Tailscale for remote access.

**Install**
Apps tab > search "VYZN". Set your Media path (mounted read-only) and Timezone, then open the WebUI. A first-run wizard walks you through the TMDB setup; no API key is needed up front.

**Notes**
- Tested on amd64 with an Intel iGPU. arm64 images are built but not tested on real hardware.
- Android TV app: download the APK from the GitHub releases page.
- Source and issues: https://github.com/comsoll8/vyzn
- This product uses the TMDB API but is not endorsed or certified by TMDB.

Please post logs (`docker logs vyzn`) and your Unraid version when reporting problems.
