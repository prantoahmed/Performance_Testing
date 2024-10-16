
# Performance Testing

## Dear, 

### I’ve completed performance test on frequently used API for test App. 
Test executed for the below mentioned scenario in server 000.000.000.00. 



20 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 40 And Total Concurrent API requested: 0.67
50 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 150 And Total Concurrent API requested: 0.03
100 Concurrent Request with 1 Loop Count; Avg TPS for Total Samples is ~ 300 And Total Concurrent API requested: 1.667
200 Concurrent Request with 10 Loop Count; Avg TPS for Total Samples is ~ 600 And Total Concurrent API requested: 3.33

While executed 200 concurrent request, found  82 request got connection timeout and error rate is 0.23%. 

Summary: Server can handle almost concurrent 200 API call with almost zero (0) error rate.

Please find the details report from the attachment and  let me know if you have any further queries.

