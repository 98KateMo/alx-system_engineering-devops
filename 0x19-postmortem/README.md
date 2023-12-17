Keitumetse Molefe
Post-mortem outage - 0x19. Post-Mortem
Due date: 18th December 2023


                                                         Summary of outage

A widely used e-commerce website experienced a service outage on 20th December, 2023, resulting in users being unable to browse the site, add items to their carts, or complete transactions. The outage lasted for a total of two hours during peak shopping hours. The web platform is similar to a retail online shop such as “Shein” where users shop for clothing items or accessories, with the end goal of making an online purchase and having their purchased items delivered to them.

                                          Timeline of events (20th December 2023)

2:00 PM: Reports of users unable to access the website and experiencing slow page load times (Issue detection). 
2:15 PM: Automated monitoring systems triggered alerts for increased error rates and server response times.
2:30 PM: Incident response team initiated an investigation into the root cause of the performance degradation.
3:30 PM: Identification of a database connection pool exhaustion as the primary cause of the service outage.
4:00 PM: Database connection pool issue resolved, and normal functionality restored.

                                                      Root cause and resolution

Root causes include lack of proactive monitoring for database connection pool metrics, incomplete testing of the application's ability to scale under peak load conditions and the absence of automated alerts for abnormal database performance patterns. The root cause of this service outage was also identified as a misconfiguration in the database connection pool settings. As more users logged onto the web platform and user traffic increased, the application server was unable to efficiently manage the available database connections which in turn resulted in a bottleneck and subsequently, performance degradation.

                                              Corrective and preventative measures

The incident response team responded promptly to user reports and automated alerts, initiating a thorough investigation. Once the misconfiguration in the database connection pool settings was identified, corrective actions were taken to resolve the issue and restore normal operation. Enhance monitoring systems to include database connection pool metrics. Conduct regular load testing to identify and address scalability issues. Implement automated alerts for abnormal performance patterns to expedite incident response.

                                        How was this service outage reported?

A detailed post-mortem report was compiled, encompassing the incident timeline, root cause analysis, contributing factors, lessons learned, and recommendations for preventive measures. This service outage report was shared amongst all of the team members and analysed meticulously by the operations team, and relevant stakeholders to guide future improvements and ensure the continued reliability of the web application.

