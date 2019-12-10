# Understand Jenkins Jobs and Builds

{% hint style="info" %}
Role:  
Technical Manager

Where:  
Jenkins dashboards are available from the **Technical Management** drop-down list.
{% endhint %}

As a technical manager of a project, you have concerns about aspects of your Jenkins jobs and builds. You want to understand what jobs and their corresponding builds have long duration times or high percentages of failures or instabilities so your team can work to increase efficiency. You may also want to know how quickly the builds are getting fixed, or if some test cases are permanently failing and either need updating or reviewing.

**Do these steps:**

1. Click a **project name** of interest.
2. From the **Technical Management** drop-down list, select **Jenkins** &gt; **Overview**.  
   A dashboard show Jenkins overview data:

   **Summary** shows the number of builds, jobs, nodes, and average build duration in minutes.

   **Results** shows a doughnut chart that represents the total number of builds in the project by status: SUCCESS, FAILURE, UNSTABLE, ABORTED. Mouse over a color in the chart to see the status, the total number of builds for the status, and the percentage of the project's builds for that status.

   **Nodes** show a table of nodes, which are machines in your Jenkins environment. For each node, the table shows the node name, the number of builds on the node, the 50th percentile of builds duration in minutes, and builds duration in minutes.

   **Builds over time** shows a bar graph that represents the number of builds per day over time.

   **Active nodes over time** shows a bar graph that represents the number of active nodes per day over time.

   **Builds** shows a table of the number of builds, 50th percentile of build duration in minutes, builds duration, success, and failures. The 50th percentile number indicates the median number of minutes that builds took to complete. This number indicates that 50 percent of the builds took longer than that number and 50 percent of the builds took less time that number. A 50th percentile is the same as a median. Click **+info** to go to Jenkins and view the build details.

3. Use the visualizations to understand various build aspects of the project. For example, each new build must go through a series of steps including compilation, testing, and validation. You want these steps to be optimized to ensure that changes are delivered quickly. The longer the build process takes, the longer it takes for changes to make their way into production. The **Builds** table shows the total time to complete a build \(in seconds\). By seeing the build time for a particular job, you can understand the build process and monitor it for abnormalities. If a build ends too quickly or takes too long, it could indicate a problem with the build server or the build pipeline.
4. From the **Technical Management** drop-down list, select **Jenkins** &gt; **Jobs**.  
   A dashboard show Jenkins job data:Jenkins &gt; Jobs

   **Summary** shows the number of builds, jobs, nodes, and average build duration in minutes.

   **Results** shows a doughnut chart that represents the total number of jobs in the project by status: SUCCESS, FAILURE, UNSTABLE, ABORTED. Mouse over a color in the chart to see the status, total number of jobs for the status, and the percentage of the project's jobs for that status. 

   **Jobs** shows a bar graph that represents the number of jobs per day over time.

   **Duration Trend** shows the time in minutes for the total number of jobs per day over time and a trend line to show an increase, decrease, or stability in the job time.

   **Jobs** shows a table of the number of builds, 50th percentile of build duration in minutes, builds duration, success, and failures. The 50th percentile number indicates the median number of minutes that builds took to complete. This number indicates that 50 percent of the builds took longer than that number and 50 percent of the builds took less time that number. A 50th percentile is the same as a median.

   **Success/Failures in percentage** shows a stacked bar graph with each value as a percentage of the total count of jobs per day over time. Mouse over Success or Failures to show the corresponding data in the graph.

   **Nodes** show a table of nodes, which are machines that are part of your Jenkins environment. For each node, the table shows the node name, \# Builds, 50th percentile of Builds duration \(median, min.\), Builds duration \(total, min.\), Success, and Failures.

5. Use the visualizations to understand various job aspects of the project. **Success/Failures in percentage** is useful because it shows the ratio of successful jobs to unsuccessful jobs, and how healthy your jobs are in builds. You can see the build and job health as a total and see how it has changed over time.

