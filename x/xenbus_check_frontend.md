# Function: <code>xenbus_check_frontend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff814d1547)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:403
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81522257)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:396
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8154e737)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:398
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81562c81)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:397
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff815c6f81)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:399
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff815ff71d)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:399
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8161a7ed)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:399
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8164e57d)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:400
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81670a5d)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:400
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xenbus_check_frontend(char *class, char *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:421
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
```
**Symbols:**

```
ffffffff81720f50-ffffffff817210a4: xenbus_check_frontend (STB_LOCAL)
ffffffff817213af-ffffffff81721499: xenbus_check_frontend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xenbus_check_frontend(char *class, char *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:421
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
```
**Symbols:**

```
ffffffff8173deb0-ffffffff8173e004: xenbus_check_frontend (STB_LOCAL)
ffffffff81c05938-ffffffff81c05a22: xenbus_check_frontend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81721abc)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:421
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff817a08dc)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:421
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff818da416)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:413
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81a2d42f)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:413
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81a76bc6)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:413
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81ac8db6)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:413
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffff80001083bcf0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:400
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81636b1d)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:400
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8166489d)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:400
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8167ee5d)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:400
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
