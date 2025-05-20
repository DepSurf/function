# Function: <code>cec_transmit_msg_fh</code>

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
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int cec_transmit_msg_fh(struct cec_adapter *adap, struct cec_msg *msg, struct cec_fh *fh, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:719
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_log_addr
  - drivers/media/cec/cec-adap.c:cec_transmit_msg
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff8180706d-ffffffff818071f5: cec_transmit_msg_fh.cold.14 (STB_LOCAL)
ffffffff81804d70-ffffffff81805313: cec_transmit_msg_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cec_transmit_msg_fh(struct cec_adapter *adap, struct cec_msg *msg, struct cec_fh *fh, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:732
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_log_addr
  - drivers/media/cec/cec-adap.c:cec_transmit_msg
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff818489a9-ffffffff81848b6a: cec_transmit_msg_fh.cold (STB_LOCAL)
ffffffff818467f0-ffffffff81846e38: cec_transmit_msg_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cec_transmit_msg_fh(struct cec_adapter *adap, struct cec_msg *msg, struct cec_fh *fh, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:746
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_log_addr
  - drivers/media/cec/cec-adap.c:cec_transmit_msg
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff8187a1d6-ffffffff8187a397: cec_transmit_msg_fh.cold (STB_LOCAL)
ffffffff81878140-ffffffff81878788: cec_transmit_msg_fh (STB_GLOBAL)
```
</details>
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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int cec_transmit_msg_fh(struct cec_adapter *adap, struct cec_msg *msg, struct cec_fh *fh, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010abfc08)
Location: drivers/media/cec/cec-adap.c:746
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_log_addr
  - drivers/media/cec/cec-adap.c:cec_transmit_msg
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffff800010abfc08-ffff800010ac0310: cec_transmit_msg_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cec_transmit_msg_fh(struct cec_adapter *adap, struct cec_msg *msg, struct cec_fh *fh, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba1940)
Location: drivers/media/cec/cec-adap.c:746
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_log_addr
  - drivers/media/cec/cec-adap.c:cec_transmit_msg
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
c0ba1940-c0ba1fd8: cec_transmit_msg_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cec_transmit_msg_fh(struct cec_adapter *adap, struct cec_msg *msg, struct cec_fh *fh, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba1930)
Location: drivers/media/cec/cec-adap.c:746
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_log_addr
  - drivers/media/cec/cec-adap.c:cec_transmit_msg
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
c000000000ba1930-c000000000ba2210: cec_transmit_msg_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cec_transmit_msg_fh(struct cec_adapter *adap, struct cec_msg *msg, struct cec_fh *fh, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c140a)
Location: drivers/media/cec/cec-adap.c:746
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_log_addr
  - drivers/media/cec/cec-adap.c:cec_transmit_msg
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffe0006c140a-ffffffe0006c1a20: cec_transmit_msg_fh (STB_GLOBAL)
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
int cec_transmit_msg_fh(struct cec_adapter *adap, struct cec_msg *msg, struct cec_fh *fh, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:746
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_log_addr
  - drivers/media/cec/cec-adap.c:cec_transmit_msg
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81822746-ffffffff81822907: cec_transmit_msg_fh.cold (STB_LOCAL)
ffffffff818206b0-ffffffff81820cf8: cec_transmit_msg_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cec_transmit_msg_fh(struct cec_adapter *adap, struct cec_msg *msg, struct cec_fh *fh, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:746
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_log_addr
  - drivers/media/cec/cec-adap.c:cec_transmit_msg
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff817e9de6-ffffffff817e9fa7: cec_transmit_msg_fh.cold (STB_LOCAL)
ffffffff817e7d50-ffffffff817e8398: cec_transmit_msg_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cec_transmit_msg_fh(struct cec_adapter *adap, struct cec_msg *msg, struct cec_fh *fh, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:746
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_log_addr
  - drivers/media/cec/cec-adap.c:cec_transmit_msg
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff8186f686-ffffffff8186f847: cec_transmit_msg_fh.cold (STB_LOCAL)
ffffffff8186d5f0-ffffffff8186dc38: cec_transmit_msg_fh (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cec_transmit_msg_fh(struct cec_adapter *adap, struct cec_msg *msg, struct cec_fh *fh, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:746
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_thread_func
  - drivers/media/cec/cec-adap.c:cec_config_log_addr
  - drivers/media/cec/cec-adap.c:cec_transmit_msg
  - drivers/media/cec/cec-api.c:cec_ioctl
```
**Symbols:**

```
ffffffff81889606-ffffffff818897c7: cec_transmit_msg_fh.cold (STB_LOCAL)
ffffffff81887570-ffffffff81887bb8: cec_transmit_msg_fh (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
