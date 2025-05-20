# Function: <code>xenbus_reset_state</code>

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
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff814d14d0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:436
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
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff815221e0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:429
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
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8154e6c0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:431
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
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81562c0f)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:430
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
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff815c6f0f)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:432
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
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff815ff6a0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:432
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
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8161a770)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:432
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
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8164e510)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:433
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
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff816709f0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:433
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xenbus_reset_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff817210b0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:454
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff817210b0-ffffffff81721189: xenbus_reset_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xenbus_reset_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8173e010)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:454
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff8173e010-ffffffff8173e0e9: xenbus_reset_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xenbus_reset_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:454
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff81721a20-ffffffff81721c3f: xenbus_reset_state (STB_LOCAL)
ffffffff81bf75c8-ffffffff81bf76cf: xenbus_reset_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xenbus_reset_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:454
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff817a0840-ffffffff817a0a5f: xenbus_reset_state (STB_LOCAL)
ffffffff81cf64c7-ffffffff81cf65ce: xenbus_reset_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xenbus_reset_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff818da340-ffffffff818da5be: xenbus_reset_state (STB_LOCAL)
ffffffff81ebe5e9-ffffffff81ebe6ee: xenbus_reset_state.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xenbus_reset_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81a2d370)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff81a2d370-ffffffff81a2d567: xenbus_reset_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xenbus_reset_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81a76b20)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff81a76b20-ffffffff81a76d0c: xenbus_reset_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xenbus_reset_state();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81ac8d10)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff81ac8d10-ffffffff81ac8efc: xenbus_reset_state (STB_LOCAL)
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
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffff80001083bc50)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:433
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
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81636ab0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:433
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
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81664830)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:433
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
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8167edf0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:433
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
