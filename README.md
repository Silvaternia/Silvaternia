## Hi there 👋

name: Silvaternia
uses: lowlighter/metrics@latest
with:
  filename: metrics.classic.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: header, repositories
  plugin_lines: yes
