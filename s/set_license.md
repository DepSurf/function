# Function: <code>set_license</code>

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
In kernel/module.c (ffffffff81107dce)
Location: kernel/module.c:2285
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff8110f245)
Location: kernel/module.c:2408
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff81116af1)
Location: kernel/module.c:2420
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff81118063)
Location: kernel/module.c:2447
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff81123667)
Location: kernel/module.c:2455
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff81131ba3)
Location: kernel/module.c:2450
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff8113d1d0)
Location: kernel/module.c:2451
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff8114895e)
Location: kernel/module.c:2451
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
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
In kernel/module.c (ffffffff81152c14)
Location: kernel/module.c:2508
Inline: True
Inline callers:
  - kernel/module.c:check_modinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void set_license(struct module *mod, const char *license);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2502
Inline: False
Direct callers:
  - kernel/module.c:check_modinfo
```
**Symbols:**

```
ffffffff81163250-ffffffff81163337: set_license (STB_LOCAL)
ffffffff81167a82-ffffffff81167a9a: set_license.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void set_license(struct module *mod, const char *license);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:2589
Inline: False
Direct callers:
  - kernel/module.c:check_modinfo
```
**Symbols:**

```
ffffffff8115f4b0-ffffffff8115f597: set_license (STB_LOCAL)
ffffffff81be3fde-ffffffff81be3ff6: set_license.cold (STB_LOCAL)
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
In kernel/module.c (ffffffff81160c31)
Location: kernel/module.c:2513
Inline: True
Inline callers:
  - kernel/module.c:check_modinfo
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
In kernel/module.c (ffffffff81185e00)
Location: kernel/module.c:2515
Inline: True
Inline callers:
  - kernel/module.c:check_modinfo
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
In kernel/module/main.c (ffffffff8118c191)
Location: kernel/module/main.c:1510
Inline: True
Inline callers:
  - kernel/module/main.c:check_modinfo
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
In kernel/module/main.c (ffffffff811c89b7)
Location: kernel/module/main.c:1508
Inline: True
Inline callers:
  - kernel/module/main.c:check_modinfo
```
</details>
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c3a00)
Location: kernel/module.c:2508
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040aba4)
Location: kernel/module.c:2508
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (c00000000022a31c)
Location: kernel/module.c:2508
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000144862)
Location: kernel/module.c:2508
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
```
</details>
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
In kernel/module.c (ffffffff8114b234)
Location: kernel/module.c:2508
Inline: True
Inline callers:
  - kernel/module.c:check_modinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113e4e4)
Location: kernel/module.c:2508
Inline: True
Inline callers:
  - kernel/module.c:check_modinfo
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811490e4)
Location: kernel/module.c:2508
Inline: True
Inline callers:
  - kernel/module.c:check_modinfo
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
In kernel/module.c (ffffffff81155da4)
Location: kernel/module.c:2508
Inline: True
Inline callers:
  - kernel/module.c:check_modinfo
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
