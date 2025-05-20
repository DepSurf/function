# Function: <code>xenbus_reset_wait_for_backend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void xenbus_reset_wait_for_backend(char *be, int expected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff816f42f8)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:351
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff816f42f8-ffffffff816f43e2: xenbus_reset_wait_for_backend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void xenbus_reset_wait_for_backend(char *be, int expected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81759358)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:344
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff81759358-ffffffff81759442: xenbus_reset_wait_for_backend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void xenbus_reset_wait_for_backend(char *be, int expected);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff817858d2)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:346
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff817858d2-ffffffff817859b0: xenbus_reset_wait_for_backend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81562e64)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:345
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff81562efd-ffffffff81562fc9: xenbus_reset_wait_for_backend.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff815c7164)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:345
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff815c71fd-ffffffff815c72c9: xenbus_reset_wait_for_backend.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff815ffa95)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:345
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff815ff92f-ffffffff815ff9ff: xenbus_reset_wait_for_backend.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8161ab65)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:345
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff8161a9ff-ffffffff8161aacf: xenbus_reset_wait_for_backend.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8164e8ec)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:346
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff8164e78c-ffffffff8164e854: xenbus_reset_wait_for_backend.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81670dcc)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:346
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff81670c6c-ffffffff81670d34: xenbus_reset_wait_for_backend.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void xenbus_reset_wait_for_backend(char *be, int expected);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff817212d6)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:367
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
```
**Symbols:**

```
ffffffff817212d6-ffffffff817213af: xenbus_reset_wait_for_backend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void xenbus_reset_wait_for_backend(char *be, int expected);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81c0585f)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:367
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_check_frontend
```
**Symbols:**

```
ffffffff81c0585f-ffffffff81c05938: xenbus_reset_wait_for_backend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xenbus_reset_wait_for_backend(char *be, int expected);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81bf74ef)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:367
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
```
**Symbols:**

```
ffffffff81bf74ef-ffffffff81bf75c8: xenbus_reset_wait_for_backend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xenbus_reset_wait_for_backend(char *be, int expected);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81cf63ee)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:367
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
```
**Symbols:**

```
ffffffff81cf63ee-ffffffff81cf64c7: xenbus_reset_wait_for_backend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xenbus_reset_wait_for_backend(char *be, int expected);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81ebe4ef)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:359
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_state
```
**Symbols:**

```
ffffffff81ebe4ef-ffffffff81ebe5e9: xenbus_reset_wait_for_backend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81a2d2c0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:359
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
```
**Symbols:**

```
ffffffff81a2d000-ffffffff81a2d108: xenbus_reset_wait_for_backend.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81a76a1b)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:359
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
```
**Symbols:**

```
ffffffff81a767b0-ffffffff81a768b8: xenbus_reset_wait_for_backend.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81ac8c0b)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:359
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
  - drivers/xen/xenbus/xenbus_probe_frontend.c:xenbus_reset_frontend
```
**Symbols:**

```
ffffffff81ac89a0-ffffffff81ac8aa8: xenbus_reset_wait_for_backend.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffff80001083bef0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:346
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffff80001083bfa4-ffff80001083c0ac: xenbus_reset_wait_for_backend.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81636e8c)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:346
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff81636d2c-ffffffff81636df4: xenbus_reset_wait_for_backend.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81664c0c)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:346
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff81664aac-ffffffff81664b74: xenbus_reset_wait_for_backend.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff8167f1cc)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:346
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
Direct callers:
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
  - drivers/xen/xenbus/xenbus_probe_frontend.c:frontend_probe_and_watch
```
**Symbols:**

```
ffffffff8167f06c-ffffffff8167f134: xenbus_reset_wait_for_backend.part.0 (STB_LOCAL)
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
</ul>
