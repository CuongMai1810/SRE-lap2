# API Service

| Category     | SLI | SLO                                                                                                         |
|--------------|-----|-------------------------------------------------------------------------------------------------------------|
| Availability |  Number of successful request ÷ Total number of requests x 100 (to get percentage)	  | 99%                                                                                                         |
| Latency      |  Requests shows 90th percentile over the last 30 seconds	   | 90% of requests below 100ms                                                                                 |
| Error Budget |  The number of error requests / total number of requests   | Error budget is defined at 20%. This means that 20% of the requests can fail and still be within the budget |
| Throughput   |  Amount of successful requests over a given time period (ex: 5 minutes)  | 5 RPS indicates the application is functioning                                                              |