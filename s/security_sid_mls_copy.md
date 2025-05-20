# Function: <code>security_sid_mls_copy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_sid_mls_copy(u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81359a80)
Location: security/selinux/ss/services.c:2732
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
ffffffff81359a80-ffffffff81359cf7: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_sid_mls_copy(u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138fa30)
Location: security/selinux/ss/services.c:2726
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff8138fa30-ffffffff8138fca7: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_sid_mls_copy(u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a6650)
Location: security/selinux/ss/services.c:2726
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff813a6650-ffffffff813a68c7: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_sid_mls_copy(u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bd0a0)
Location: security/selinux/ss/services.c:2842
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff813bd0a0-ffffffff813bd2fe: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_sid_mls_copy(u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e3210)
Location: security/selinux/ss/services.c:2852
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff813e3210-ffffffff813e346e: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2977
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff81414d77-ffffffff81414dd2: security_sid_mls_copy.cold.38 (STB_LOCAL)
ffffffff814139b0-ffffffff81413bef: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2943
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff81431332-ffffffff8143138d: security_sid_mls_copy.cold.38 (STB_LOCAL)
ffffffff8142fee0-ffffffff81430136: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2956
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff8145eddf-ffffffff8145ee58: security_sid_mls_copy.cold (STB_LOCAL)
ffffffff8145d870-ffffffff8145dadd: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2963
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff81478b91-ffffffff81478c0a: security_sid_mls_copy.cold (STB_LOCAL)
ffffffff81477620-ffffffff8147788d: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3002
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff814ce03a-ffffffff814ce0a7: security_sid_mls_copy.cold (STB_LOCAL)
ffffffff814cca60-ffffffff814ccce6: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3120
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff81bf1094-ffffffff81bf1102: security_sid_mls_copy.cold (STB_LOCAL)
ffffffff814ea250-ffffffff814ea4b3: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3198
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff81be31e2-ffffffff81be3245: security_sid_mls_copy.cold (STB_LOCAL)
ffffffff814f0e50-ffffffff814f111f: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3205
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff81cd5186-ffffffff81cd5220: security_sid_mls_copy.cold (STB_LOCAL)
ffffffff8154b430-ffffffff8154b727: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3207
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff81e87fd3-ffffffff81e88065: security_sid_mls_copy.cold (STB_LOCAL)
ffffffff815e4200-ffffffff815e4543: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3200
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff82073e5e-ffffffff82073e94: security_sid_mls_copy.cold (STB_LOCAL)
ffffffff81693520-ffffffff816938ae: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_sid_mls_copy(u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3147
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff820f3a0f-ffffffff820f3a45: security_sid_mls_copy.cold (STB_LOCAL)
ffffffff816cba30-ffffffff816cbdb0: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_sid_mls_copy(u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3156
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff821d0bd5-ffffffff821d0c0b: security_sid_mls_copy.cold (STB_LOCAL)
ffffffff817086f0-ffffffff81708a70: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010567348)
Location: security/selinux/ss/services.c:2963
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffff800010567348-ffff800010567620: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071b868)
Location: security/selinux/ss/services.c:2963
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
c071b868-c071bb28: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006ca700)
Location: security/selinux/ss/services.c:2963
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
c0000000006ca700-c0000000006caaa0: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bd07a)
Location: security/selinux/ss/services.c:2963
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffe0003bd07a-ffffffe0003bd2c4: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2963
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff81471171-ffffffff814711ea: security_sid_mls_copy.cold (STB_LOCAL)
ffffffff8146fc00-ffffffff8146fe6d: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2963
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff81461b91-ffffffff81461c0a: security_sid_mls_copy.cold (STB_LOCAL)
ffffffff81460620-ffffffff8146088d: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2963
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff8146d211-ffffffff8146d28a: security_sid_mls_copy.cold (STB_LOCAL)
ffffffff8146bca0-ffffffff8146bf0d: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int security_sid_mls_copy(struct selinux_state *state, u32 sid, u32 mls_sid, u32 *new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2963
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_conn_request
  - security/selinux/hooks.c:selinux_sctp_assoc_request
  - security/selinux/hooks.c:selinux_socket_unix_stream_connect
```
**Symbols:**

```
ffffffff81484a7d-ffffffff81484af6: security_sid_mls_copy.cold (STB_LOCAL)
ffffffff81483450-ffffffff814836bc: security_sid_mls_copy (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>sid, mls_sid, new_sid</code> ➡️ <code>state, sid, mls_sid, new_sid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, sid, mls_sid, new_sid</code> ➡️ <code>sid, mls_sid, new_sid</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
