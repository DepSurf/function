# Function: <code>wait_loop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff814d11b0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:263
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff814d11b0-ffffffff814d123f: wait_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81521ec0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:256
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff81521ec0-ffffffff81521f4f: wait_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8154e390)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:256
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff8154e390-ffffffff8154e41f: wait_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81562820)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:255
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff81562820-ffffffff815628af: wait_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff815c6b20)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:255
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff815c6b20-ffffffff815c6baf: wait_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:255
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff815ff310-ffffffff815ff353: wait_loop (STB_LOCAL)
ffffffff815ff8ab-ffffffff815ff902: wait_loop.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:255
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff8161a3e0-ffffffff8161a423: wait_loop (STB_LOCAL)
ffffffff8161a97b-ffffffff8161a9d2: wait_loop.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:256
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff8164e190-ffffffff8164e1d3: wait_loop (STB_LOCAL)
ffffffff8164e70a-ffffffff8164e75f: wait_loop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:256
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff81670670-ffffffff816706b3: wait_loop (STB_LOCAL)
ffffffff81670bea-ffffffff81670c3f: wait_loop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:277
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff81720c70-ffffffff81720cb2: wait_loop (STB_LOCAL)
ffffffff81721254-ffffffff817212a9: wait_loop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:277
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff8173dbd0-ffffffff8173dc12: wait_loop (STB_LOCAL)
ffffffff81c057dd-ffffffff81c05832: wait_loop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:277
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff81721750-ffffffff81721790: wait_loop (STB_LOCAL)
ffffffff81bf7478-ffffffff81bf74c2: wait_loop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:277
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff817a0570-ffffffff817a05b0: wait_loop (STB_LOCAL)
ffffffff81cf6377-ffffffff81cf63c1: wait_loop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:269
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff818d9f90-ffffffff818d9fec: wait_loop (STB_LOCAL)
ffffffff81ebe478-ffffffff81ebe4c2: wait_loop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81a2cb60)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:269
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff81a2cb60-ffffffff81a2cbfd: wait_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81a76310)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:269
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff81a76310-ffffffff81a763ad: wait_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81ac8500)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:269
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff81ac8500-ffffffff81ac859d: wait_loop (STB_LOCAL)
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
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffff80001083b760)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:256
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffff80001083b760-ffff80001083b810: wait_loop (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:256
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff81636730-ffffffff81636773: wait_loop (STB_LOCAL)
ffffffff81636caa-ffffffff81636cff: wait_loop.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:256
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff816644b0-ffffffff816644f3: wait_loop (STB_LOCAL)
ffffffff81664a2a-ffffffff81664a7f: wait_loop.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool wait_loop(long unsigned int start, unsigned int max_delay, unsigned int *seconds_waited);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:256
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_for_devices
```
**Symbols:**

```
ffffffff8167ea70-ffffffff8167eab3: wait_loop (STB_LOCAL)
ffffffff8167efea-ffffffff8167f03f: wait_loop.cold (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
