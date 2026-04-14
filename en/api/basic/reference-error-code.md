---
title: API error codes
---

<table class="table table-big">
  <thead>
    <tr>
      <th>Error name</th>
      <th>HTTP status</th>
      <th>Description</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>INVALID\_API\_KEY</td>
      <td>403</td>
      <td>No API key was provided</td>
    </tr>

    <tr>
      <td>MODEL\_NOT\_FOUND</td>
      <td>404</td>
      <td>Model does not exist</td>
    </tr>

    <tr>
      <td>FAILED\_TO\_AUTH</td>
      <td>401</td>
      <td>Authentication failed</td>
    </tr>

    <tr>
      <td>NOT\_ENOUGH\_BALANCE</td>
      <td>403</td>
      <td>Insufficient balance</td>
    </tr>

    <tr>
      <td>INVALID\_REQUEST\_BODY</td>
      <td>400</td>
      <td>Invalid request body format; see message for details</td>
    </tr>

    <tr>
      <td>RATE\_LIMIT\_EXCEEDED</td>
      <td>429</td>
      <td>Rate limit exceeded; try again later</td>
    </tr>

    <tr>
      <td>TOKEN\_LIMIT\_EXCEEDED</td>
      <td>429</td>
      <td>Token limit exceeded; try again later</td>
    </tr>

    <tr>
      <td>SERVICE\_NOT\_AVAILABLE</td>
      <td>503</td>
      <td>Service unavailable</td>
    </tr>

    <tr>
      <td>ACCESS\_DENY</td>
      <td>403</td>
      <td>Access denied</td>
    </tr>

  </tbody>
</table>
