# Steps to export dashboard

- Go to https://awepytorch.grafana.net.
- Select the dashboard
- On top left corner there is share icon called: "Share dashboard or panel"
- Pick export tab
- Check "Export for sharing externally"
- Save to file.

# Steps to import dashboard

- Go to https://awepytorch.grafana.net.
- In side panel pick Dashboard -> Import (it's directly in that context menu).
- Pick AWE-Pytorch.json file and import it as new dashboard.
- Perform comparison with your old dashboard.
- Copy missing/updated imported panels into old dashboard.
  - Left click on title of panel
  - Pick copy
  - Go to dashboard where you'd like to copy it to.
  - Click on Add Panel -> JSON in clipboard.