<table>
<tbody>
<tr class="odd">
<td>NAME</td>
<td>PROMPT</td>
<td>DESCRIPTION</td>
<td>EXAMPLE</td>
</tr>

<tr class="even">
<td>Simple pod</td>
<td>create pod nginx</td>
<td>creates pod nginx</td>
<td><a href="app.yaml">app.yaml</a></td>
</tr>

<tr class="even">
<td>Pod with liveness probe</td>
<td>create pod with livenessProbe</td>
<td>creates nginx pod with liveness probe</td>
<td><a href="app-livenessProbe.yaml">app-livenessProbe.yaml</a></td>
</tr>

<tr class="even">
<td>Pod with readiness probe</td>
<td>create pod with readiness probe</td>
<td>creates nginx pod with readiness probe</td>
<td><a href="app-readinessProbe.yaml">app-readinessProbe.yaml</a></td>
</tr>

<tr class="even">
<td>Volume</td>
<td>create pod with readiness and liveness probe and with volume</td>
<td>Pod with volume</td>
<td><a href="app-volumeMounts.yaml">app-volumeMounts.yaml</a></td>
</tr>

<tr class="even">
<td>Cron job</td>
<td>create cron job</td>
<td>Creates scheduled job</td>
<td><a href="app-cronjob.yaml">app-cronjob.yaml</a></td>
</tr>

<tr class="even">
<td>Job</td>
<td>create job with volume</td>
<td>Creates job</td>
<td><a href="app-job.yaml">app-job.yaml</a></td>
</tr>

<tr class="even">
<td>Multi container manifest</td>
<td>create pod with nginx and busybox and volume</td>
<td>Creates 2 pods</td>
<td><a href="app-multicontainer.yaml">app-multicontainer.yaml</a></td>
</tr>

<tr class="even">
<td>Resources</td>
<td>create pod with nginx and busybox and resources</td>
<td>Creates pod with restricted resources</td>
<td><a href="app-resources.yaml">app-resources.yaml</a></td>
</tr>

<tr class="even">
<td>Secret env vars</td>
<td>redis pod with secret env</td>
<td>Creates pod with secret env</td>
<td><a href="app-secret-env.yaml">app-secret-env.yaml</a></td>
</tr>

</tbody>
</table>