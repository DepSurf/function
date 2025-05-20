# Function: <code>klp_free_patch_finish</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void klp_free_patch_finish(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8111f4a0)
Location: kernel/livepatch/core.c:651
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_free_patch_work_fn
```
**Symbols:**

```
ffffffff8111f4a0-ffffffff8111f4d6: klp_free_patch_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void klp_free_patch_finish(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112bbf0)
Location: kernel/livepatch/core.c:651
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_free_patch_work_fn
```
**Symbols:**

```
ffffffff8112bbf0-ffffffff8112bc26: klp_free_patch_finish (STB_LOCAL)
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
In kernel/livepatch/core.c (ffffffff8113ad99)
Location: kernel/livepatch/core.c:673
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_patch_work_fn
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
In kernel/livepatch/core.c (ffffffff81135889)
Location: kernel/livepatch/core.c:673
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_patch_work_fn
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
In kernel/livepatch/core.c (ffffffff8113672b)
Location: kernel/livepatch/core.c:672
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_patch_work_fn
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
In kernel/livepatch/core.c (ffffffff81159349)
Location: kernel/livepatch/core.c:672
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_patch_work_fn
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
In kernel/livepatch/core.c (ffffffff811828dd)
Location: kernel/livepatch/core.c:672
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_patch_work_fn
  - kernel/livepatch/core.c:klp_free_patch_work_fn
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
In kernel/livepatch/core.c (ffffffff811bd5e3)
Location: kernel/livepatch/core.c:697
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_patch_work_fn
  - kernel/livepatch/core.c:klp_free_patch_work_fn
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
In kernel/livepatch/core.c (ffffffff811cfdee)
Location: kernel/livepatch/core.c:712
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_patch_work_fn
  - kernel/livepatch/core.c:klp_free_patch_work_fn
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
In kernel/livepatch/core.c (ffffffff811e4a3e)
Location: kernel/livepatch/core.c:712
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_patch_work_fn
  - kernel/livepatch/core.c:klp_free_patch_work_fn
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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void klp_free_patch_finish(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (c0000000001ef1b0)
Location: kernel/livepatch/core.c:651
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_free_patch_work_fn
```
**Symbols:**

```
c0000000001ef1b0-c0000000001ef230: klp_free_patch_finish (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void klp_free_patch_finish(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811241d0)
Location: kernel/livepatch/core.c:651
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_free_patch_work_fn
```
**Symbols:**

```
ffffffff811241d0-ffffffff81124206: klp_free_patch_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void klp_free_patch_finish(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81116c30)
Location: kernel/livepatch/core.c:651
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_free_patch_work_fn
```
**Symbols:**

```
ffffffff81116c30-ffffffff81116c66: klp_free_patch_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void klp_free_patch_finish(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811220c0)
Location: kernel/livepatch/core.c:651
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_free_patch_work_fn
```
**Symbols:**

```
ffffffff811220c0-ffffffff811220f6: klp_free_patch_finish (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void klp_free_patch_finish(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112e6d0)
Location: kernel/livepatch/core.c:651
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_free_patch_work_fn
```
**Symbols:**

```
ffffffff8112e6d0-ffffffff8112e706: klp_free_patch_finish (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
