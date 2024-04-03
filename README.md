---
datapackage:
  title: Hackathon Task 2
  description: This is my second task for the Cloud Datahub Hackathon
  resources:
    - path: data.csv
      title: Bitcoin - USD
      name: btc-usd
      format: csv
      schema:
        fields:
          - name: date
            type: date
          - name: open
            type: number
          - name: high
            type: number
          - name: low
            type: number
          - name: close
            type: number
          - name: adj close
            type: number
          - name: volume
            type: number
---

This is the second task for the amazing Cloud Datahub Hackathon!

## Excel

<Excel url="data.csv" />

## Line Chart

<LineChart data="data.csv" xAxis="Date" yAxis="Open" yAxisType="temporal" fullWidth/>
