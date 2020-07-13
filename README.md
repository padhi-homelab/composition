# Services <a href='https://github.com/padhi-homelab/Services/actions?query=workflow%3A%22Docker+CI+Release%22'><img align='right' src='https://img.shields.io/github/workflow/status/padhi-homelab/Services/Docker%20CI%20Release?logo=github&logoWidth=24&style=flat-square'></img></a>

### Architecture Support Matrix

<table>
  <thead>
    <tr>
      <th colspan='3'>&#x2B9F; Services &nbsp; &nbsp; &nbsp; \ &nbsp; &nbsp; &nbsp; Arch &#x2B9E;</th>
      <th>amd64</th>
      <th>i386</th>
      <th>arm/v6</th>
      <th>arm/v7</th>
      <th>arm64</th>
      <th>ppc64le</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>
        ✰ <br> 🞅
      </th>
      <th align='right'>
        <a href='https://hub.docker.com/repository/docker/padhihomelab/dnscrypt-proxy'>
          dnscrypt-proxy
        </a>
        <br>
        <a href='https://hub.docker.com/r/pihole/pihole/'>
          pihole
        </a>
      </th>
      <td align='center'>
        <code>2.0.44</code>
        <br>
        <code>v5.0</code>
      </td>
      <td align='center'>
        :heavy_check_mark:
      </td>
      <td align='center'>
        :heavy_check_mark:
      </td>
      <td align='center'>
        :heavy_check_mark:
      </td>
      <td align='center'>
        :heavy_check_mark:
      </td>
      <td align='center'>
        :heavy_check_mark:
      </td>
      <td align='center'>
        :heavy_multiplication_x:
        <br>
        [ :heavy_check_mark: :heavy_multiplication_x: ]
      </td>
    </tr>
    <tr>
      <th>
        ❍ <br> ✰
      </th>
      <th align='right'>
        <a href='https://hub.docker.com/r/padhihomelab/docker.sock-proxy/'>
          docker.sock-proxy
        </a>
        <br>
        <a href='https://hub.docker.com/r/padhihomelab/netdata/'>
          netdata
        </a>
      </th>
      <td align='center'>
        <code>2.2</code>
        <br>
        <code>v1.23.1</code>
      </td>
      <td align='center'>
        :heavy_check_mark:
      </td>
      <td align='center'>
        :heavy_check_mark:
      </td>
      <td align='center'>
        :heavy_check_mark:
      </td>
      <td align='center'>
        :heavy_check_mark:
      </td>
      <td align='center'>
        :heavy_check_mark:
      </td>
      <td align='center'>
        :heavy_check_mark:
      </td>
    </tr>
  </tbody>
</table>

✰&nbsp;
Dockerfiles maintained by me using binaries compiled from sources
<br>
❍&nbsp;
Dockerfiles maintained by me, but with pre-compiled binaries from open-source projects
<br>
🞅&nbsp;
Official dockerfiles (and binaries) from open-source projects
<br>
🞉&nbsp;
Third-party dockerfiles devoid of closed-source binaries
<br>
🅧&nbsp;
Dockerfiles containing closed-source binaries (blobs)
