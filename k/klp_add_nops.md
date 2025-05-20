# Function: <code>klp_add_nops</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8111ff5a)
Location: kernel/livepatch/core.c:513
Inline: True
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
In kernel/livepatch/core.c (ffffffff8112c67b)
Location: kernel/livepatch/core.c:513
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8113ae30)
Location: kernel/livepatch/core.c:535
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81135920)
Location: kernel/livepatch/core.c:535
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int klp_add_nops(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81135e10)
Location: kernel/livepatch/core.c:534
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff81135e10-ffffffff811360bf: klp_add_nops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int klp_add_nops(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811589b0)
Location: kernel/livepatch/core.c:534
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff811589b0-ffffffff81158c5f: klp_add_nops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int klp_add_nops(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81181e80)
Location: kernel/livepatch/core.c:534
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff81181e80-ffffffff81182161: klp_add_nops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int klp_add_nops(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811bc820)
Location: kernel/livepatch/core.c:558
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff811bc820-ffffffff811bcb01: klp_add_nops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int klp_add_nops(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811cf1b0)
Location: kernel/livepatch/core.c:573
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff811cf1b0-ffffffff811cf490: klp_add_nops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int klp_add_nops(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811e3d90)
Location: kernel/livepatch/core.c:573
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff811e3d90-ffffffff811e40d2: klp_add_nops (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (c0000000001f0a40)
Location: kernel/livepatch/core.c:513
Inline: True
```
</details>
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
In kernel/livepatch/core.c (ffffffff81124c5b)
Location: kernel/livepatch/core.c:513
Inline: True
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
In kernel/livepatch/core.c (ffffffff811176bb)
Location: kernel/livepatch/core.c:513
Inline: True
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
In kernel/livepatch/core.c (ffffffff81122b4b)
Location: kernel/livepatch/core.c:513
Inline: True
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
In kernel/livepatch/core.c (ffffffff8112f15b)
Location: kernel/livepatch/core.c:513
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
