# Function: <code>process_writes</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8155da5e)
Location: drivers/xen/xenbus/xenbus_comms.c:335
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
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
In drivers/xen/xenbus/xenbus_comms.c (ffffffff815c1d6e)
Location: drivers/xen/xenbus/xenbus_comms.c:336
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
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
In drivers/xen/xenbus/xenbus_comms.c (ffffffff815fa538)
Location: drivers/xen/xenbus/xenbus_comms.c:336
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
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
In drivers/xen/xenbus/xenbus_comms.c (ffffffff816155e8)
Location: drivers/xen/xenbus/xenbus_comms.c:336
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
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
In drivers/xen/xenbus/xenbus_comms.c (ffffffff816492c0)
Location: drivers/xen/xenbus/xenbus_comms.c:336
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
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
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8166b760)
Location: drivers/xen/xenbus/xenbus_comms.c:338
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int process_writes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8171ba00)
Location: drivers/xen/xenbus/xenbus_comms.c:338
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
```
**Symbols:**

```
ffffffff8171ba00-ffffffff8171bc02: process_writes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int process_writes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81738a40)
Location: drivers/xen/xenbus/xenbus_comms.c:330
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
```
**Symbols:**

```
ffffffff81738a40-ffffffff81738c42: process_writes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int process_writes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8171c2c0)
Location: drivers/xen/xenbus/xenbus_comms.c:330
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
```
**Symbols:**

```
ffffffff8171c2c0-ffffffff8171c666: process_writes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int process_writes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8179b030)
Location: drivers/xen/xenbus/xenbus_comms.c:330
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
```
**Symbols:**

```
ffffffff8179b030-ffffffff8179b3d6: process_writes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int process_writes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff818d46c0)
Location: drivers/xen/xenbus/xenbus_comms.c:330
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
```
**Symbols:**

```
ffffffff818d46c0-ffffffff818d48d2: process_writes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int process_writes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81a26940)
Location: drivers/xen/xenbus/xenbus_comms.c:330
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
```
**Symbols:**

```
ffffffff81a26940-ffffffff81a26b52: process_writes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int process_writes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81a6ffb0)
Location: drivers/xen/xenbus/xenbus_comms.c:330
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
```
**Symbols:**

```
ffffffff81a6ffb0-ffffffff81a701c2: process_writes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int process_writes();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81ac20b0)
Location: drivers/xen/xenbus/xenbus_comms.c:330
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
```
**Symbols:**

```
ffffffff81ac20b0-ffffffff81ac22c2: process_writes (STB_LOCAL)
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
In drivers/xen/xenbus/xenbus_comms.c (ffff800010835c08)
Location: drivers/xen/xenbus/xenbus_comms.c:338
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
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
In drivers/xen/xenbus/xenbus_comms.c (ffffffff816315d0)
Location: drivers/xen/xenbus/xenbus_comms.c:338
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
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
In drivers/xen/xenbus/xenbus_comms.c (ffffffff8165f5a0)
Location: drivers/xen/xenbus/xenbus_comms.c:338
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
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
In drivers/xen/xenbus/xenbus_comms.c (ffffffff81679b9b)
Location: drivers/xen/xenbus/xenbus_comms.c:338
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_comms.c:xenbus_thread
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
