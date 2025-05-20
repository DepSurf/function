# Function: <code>wait_for_devices</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff814d1240)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:295
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
```
**Symbols:**

```
ffffffff814d1240-ffffffff814d1343: wait_for_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81521f50)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:288
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff81521f50-ffffffff81522053: wait_for_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8154e420)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:288
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff8154e420-ffffffff8154e523: wait_for_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff815628b0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:287
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff815628b0-ffffffff815629b3: wait_for_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff815c6bb0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:287
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff815c6bb0-ffffffff815c6cb3: wait_for_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:287
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff815ff360-ffffffff815ff45a: wait_for_devices (STB_LOCAL)
ffffffff815ff902-ffffffff815ff913: wait_for_devices.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:287
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff8161a430-ffffffff8161a52d: wait_for_devices (STB_LOCAL)
ffffffff8161a9d2-ffffffff8161a9e3: wait_for_devices.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:288
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff8164e1e0-ffffffff8164e2dd: wait_for_devices (STB_LOCAL)
ffffffff8164e75f-ffffffff8164e770: wait_for_devices.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:288
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff816706c0-ffffffff816707bd: wait_for_devices (STB_LOCAL)
ffffffff81670c3f-ffffffff81670c50: wait_for_devices.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:309
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff81720cc0-ffffffff81720dbd: wait_for_devices (STB_LOCAL)
ffffffff817212a9-ffffffff817212ba: wait_for_devices.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:309
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff8173dc20-ffffffff8173dd1d: wait_for_devices (STB_LOCAL)
ffffffff81c05832-ffffffff81c05843: wait_for_devices.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:309
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff81721790-ffffffff8172188d: wait_for_devices (STB_LOCAL)
ffffffff81bf74c2-ffffffff81bf74d3: wait_for_devices.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:309
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff817a05b0-ffffffff817a06ad: wait_for_devices (STB_LOCAL)
ffffffff81cf63c1-ffffffff81cf63d2: wait_for_devices.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:301
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff818d9ff0-ffffffff818da0fb: wait_for_devices (STB_LOCAL)
ffffffff81ebe4c2-ffffffff81ebe4d3: wait_for_devices.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81a2cc10)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:301
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff81a2cc10-ffffffff81a2cd24: wait_for_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81a763c0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:301
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff81a763c0-ffffffff81a764d4: wait_for_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81ac85b0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:301
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff81ac85b0-ffffffff81ac86c4: wait_for_devices (STB_LOCAL)
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
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffff80001083b810)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:288
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffff80001083b810-ffff80001083b958: wait_for_devices (STB_LOCAL)
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
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:288
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff81636780-ffffffff8163687d: wait_for_devices (STB_LOCAL)
ffffffff81636cff-ffffffff81636d10: wait_for_devices.cold (STB_LOCAL)
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
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:288
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff81664500-ffffffff816645fd: wait_for_devices (STB_LOCAL)
ffffffff81664a7f-ffffffff81664a90: wait_for_devices.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void wait_for_devices(struct xenbus_driver *xendrv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:288
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:boot_wait_for_devices
  - drivers/xen/xenbus/xenbus_probe_frontend.c:__xenbus_register_frontend
```
**Symbols:**

```
ffffffff8167eac0-ffffffff8167ebbd: wait_for_devices (STB_LOCAL)
ffffffff8167f03f-ffffffff8167f050: wait_for_devices.cold (STB_LOCAL)
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
