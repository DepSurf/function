# Function: <code>setup_load_info</code>

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
In kernel/module.c (ffffffff81107b5b)
Location: kernel/module.c:2801
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
In kernel/module.c (ffffffff8110eefb)
Location: kernel/module.c:2892
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
In kernel/module.c (ffffffff81116809)
Location: kernel/module.c:2907
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
In kernel/module.c (ffffffff81117d69)
Location: kernel/module.c:2942
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
In kernel/module.c (ffffffff81123349)
Location: kernel/module.c:2960
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
In kernel/module.c (ffffffff81131825)
Location: kernel/module.c:2983
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
In kernel/module.c (ffffffff8113dc68)
Location: kernel/module.c:2975
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff8114971e)
Location: kernel/module.c:2983
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff8115539e)
Location: kernel/module.c:3051
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int setup_load_info(struct load_info *info, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3051
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81162d50-ffffffff81162e89: setup_load_info (STB_LOCAL)
ffffffff81167a20-ffffffff81167a6e: setup_load_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int setup_load_info(struct load_info *info, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:3235
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8115f0a0-ffffffff8115f1b9: setup_load_info (STB_LOCAL)
ffffffff81be3f90-ffffffff81be3fde: setup_load_info.cold (STB_LOCAL)
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
In kernel/module.c (ffffffff81163bd0)
Location: kernel/module.c:3154
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff811892ac)
Location: kernel/module.c:3176
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module/main.c (ffffffff8118f0fe)
Location: kernel/module/main.c:1898
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
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
In kernel/module/main.c (ffffffff811cbf9e)
Location: kernel/module/main.c:1901
Inline: True
Inline callers:
  - kernel/module/main.c:load_module
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
In kernel/module.c (ffff8000101c47a0)
Location: kernel/module.c:3051
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (c040ba64)
Location: kernel/module.c:3051
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (c00000000022b9cc)
Location: kernel/module.c:3051
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffe000145138)
Location: kernel/module.c:3051
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff8114d9be)
Location: kernel/module.c:3051
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff81140c6e)
Location: kernel/module.c:3051
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff8114b86e)
Location: kernel/module.c:3051
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff8115855e)
Location: kernel/module.c:3051
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
