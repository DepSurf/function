# Function: <code>audit_log_session_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81122210)
Location: kernel/audit.c:1653
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_config_change
  - kernel/audit.c:audit_log_common_recv_msg
```
**Symbols:**

```
ffffffff81122210-ffffffff8112225a: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8112a140)
Location: kernel/audit.c:1664
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
**Symbols:**

```
ffffffff8112a140-ffffffff8112a18a: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81133e60)
Location: kernel/audit.c:1803
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
**Symbols:**

```
ffffffff81133e60-ffffffff81133eaa: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81135380)
Location: kernel/audit.c:1982
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
**Symbols:**

```
ffffffff81135380-ffffffff811353ca: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81142080)
Location: kernel/audit.c:1990
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
**Symbols:**

```
ffffffff81142080-ffffffff811420ca: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81150a50)
Location: kernel/audit.c:2043
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
```
**Symbols:**

```
ffffffff81150a50-ffffffff81150a9a: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8115d6f0)
Location: kernel/audit.c:2040
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff8115d6f0-ffffffff8115d73a: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81169e10)
Location: kernel/audit.c:2040
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff81169e10-ffffffff81169e5c: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81175cb0)
Location: kernel/audit.c:2042
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff81175cb0-ffffffff81175cfc: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81187ba6)
Location: kernel/audit.c:2122
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_fsnotify.c:audit_autoremove_mark_rule
```
**Symbols:**

```
ffffffff81188450-ffffffff8118849c: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81184f16)
Location: kernel/audit.c:2139
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_fsnotify.c:audit_autoremove_mark_rule
```
**Symbols:**

```
ffffffff811857a0-ffffffff811857ec: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81185da6)
Location: kernel/audit.c:2139
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff81186790-ffffffff811867dc: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811ae196)
Location: kernel/audit.c:2178
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff811aebc0-ffffffff811aec0c: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff811e003b)
Location: kernel/audit.c:2160
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
```
**Symbols:**

```
ffffffff811e0c10-ffffffff811e0c68: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81225d9b)
Location: kernel/audit.c:2158
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
```
**Symbols:**

```
ffffffff81226a10-ffffffff81226a68: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8123c37b)
Location: kernel/audit.c:2158
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
```
**Symbols:**

```
ffffffff8123cff0-ffffffff8123d048: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8125624a)
Location: kernel/audit.c:2176
Inline: True
Inline callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
Direct callers:
  - kernel/audit_watch.c:audit_remove_parent_watches
```
**Symbols:**

```
ffffffff81256f20-ffffffff81256f78: audit_log_session_info (STB_GLOBAL)
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
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffff8000101eac50)
Location: kernel/audit.c:2042
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffff8000101eac50-ffff8000101eaca4: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c042a8bc)
Location: kernel/audit.c:2042
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
c042a8bc-c042a914: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (c00000000025c0b0)
Location: kernel/audit.c:2042
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
c00000000025c0b0-c00000000025c120: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffe00015f5a4)
Location: kernel/audit.c:2042
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffe00015f5a4-ffffffe00015f5f8: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116e2d0)
Location: kernel/audit.c:2042
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff8116e2d0-ffffffff8116e31c: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81161470)
Location: kernel/audit.c:2042
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff81161470-ffffffff811614bc: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8116c0a0)
Location: kernel/audit.c:2042
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff8116c0a0-ffffffff8116c0ec: audit_log_session_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_log_session_info(struct audit_buffer *ab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff81179860)
Location: kernel/audit.c:2042
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_common_recv_msg
  - kernel/audit.c:audit_log_config_change
  - kernel/audit_fsnotify.c:audit_mark_handle_event
```
**Symbols:**

```
ffffffff81179860-ffffffff811798ac: audit_log_session_info (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
