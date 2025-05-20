# Function: <code>handshake_req_private</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *handshake_req_private(struct handshake_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/handshake/request.c (ffffffff82092a60)
Location: net/handshake/request.c:138
Inline: False
Direct callers:
  - net/handshake/tlshd.c:tls_server_hello_psk
  - net/handshake/tlshd.c:tls_server_hello_x509
  - net/handshake/tlshd.c:tls_client_hello_psk
  - net/handshake/tlshd.c:tls_client_hello_x509
  - net/handshake/tlshd.c:tls_client_hello_anon
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_done
```
**Symbols:**

```
ffffffff82092a60-ffffffff82092a75: handshake_req_private (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *handshake_req_private(struct handshake_req *req);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/handshake/request.c (ffffffff82169310)
Location: net/handshake/request.c:138
Inline: False
Direct callers:
  - net/handshake/tlshd.c:tls_server_hello_psk
  - net/handshake/tlshd.c:tls_server_hello_x509
  - net/handshake/tlshd.c:tls_client_hello_psk
  - net/handshake/tlshd.c:tls_client_hello_x509
  - net/handshake/tlshd.c:tls_client_hello_anon
  - net/handshake/tlshd.c:tls_handshake_accept
  - net/handshake/tlshd.c:tls_handshake_done
```
**Symbols:**

```
ffffffff82169310-ffffffff82169325: handshake_req_private (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
