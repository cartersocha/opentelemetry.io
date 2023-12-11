---
title: Synthetic Browser Testing Using Selenium and OpenTelemetry
linkTitle: Selenium Synthetic Browser Tests
date: 2023-11-07
author: '[Carter Socha](https://github.com/cartersocha)'
---

Previously I covered how to do synthetic HTTP tests using OpenTelemetry and the OpenTelemetry Collector. Now I'd like to demonstrate how OpenTelemetry and the popular synthetic testing framework Selenium can be used to create more complex browser based synthetic tests.

1. Download Selenium and rename the file
1. Download and run otel desktop viewer
1. Make Sure Java is Installed - https://www.oracle.com/java/technologies/downloads/#jdk17-mac
1. Run Selenium and give it 2 minutes to start
1. Test the server
1. Run the test
1. Look in otel desktop viewer

If you're a current user then add a jvm arg to use the otel otlp exporter with the default exporter.
