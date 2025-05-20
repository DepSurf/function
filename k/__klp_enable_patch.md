# Function: <code>__klp_enable_patch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810e9250)
Location: kernel/livepatch/core.c:473
Inline: True
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:enabled_store
```
**Symbols:**

```
ffffffff810e9250-ffffffff810e936a: __klp_enable_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int __klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810efe90)
Location: kernel/livepatch/core.c:537
Inline: True
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff810efe90-ffffffff810effac: __klp_enable_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int __klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f6a70)
Location: kernel/livepatch/core.c:535
Inline: True
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff810f6a70-ffffffff810f6b58: __klp_enable_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f77f0)
Location: kernel/livepatch/core.c:346
Inline: True
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff810f77f0-ffffffff810f78d4: __klp_enable_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81101a40)
Location: kernel/livepatch/core.c:350
Inline: True
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff81101a40-ffffffff81101b88: __klp_enable_patch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:350
Inline: True
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff81109e20-ffffffff81109e85: __klp_enable_patch (STB_LOCAL)
ffffffff8110ac4b-ffffffff8110ad39: __klp_enable_patch.cold.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int __klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8111643b)
Location: kernel/livepatch/core.c:350
Inline: True
Direct callers:
  - kernel/livepatch/core.c:enabled_store
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff811155f0-ffffffff81115655: __klp_enable_patch (STB_LOCAL)
ffffffff8111643b-ffffffff81116529: __klp_enable_patch.cold.19 (STB_LOCAL)
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
In kernel/livepatch/core.c (ffffffff8111fedf)
Location: kernel/livepatch/core.c:904
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
In kernel/livepatch/core.c (ffffffff8112c62b)
Location: kernel/livepatch/core.c:904
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:957
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff8113a250-ffffffff8113a296: __klp_enable_patch (STB_LOCAL)
ffffffff8113b29d-ffffffff8113b3a5: __klp_enable_patch.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __klp_enable_patch(struct klp_patch *patch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:957
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff81134d40-ffffffff81134d86: __klp_enable_patch (STB_LOCAL)
ffffffff81be2fac-ffffffff81be30b4: __klp_enable_patch.cold (STB_LOCAL)
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
In kernel/livepatch/core.c (ffffffff8113677b)
Location: kernel/livepatch/core.c:956
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
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
In kernel/livepatch/core.c (ffffffff811593a8)
Location: kernel/livepatch/core.c:956
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
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
In kernel/livepatch/core.c (ffffffff8118293c)
Location: kernel/livepatch/core.c:945
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
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
In kernel/livepatch/core.c (ffffffff811bd647)
Location: kernel/livepatch/core.c:970
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
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
In kernel/livepatch/core.c (ffffffff811cfe52)
Location: kernel/livepatch/core.c:998
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
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
In kernel/livepatch/core.c (ffffffff811e4aa2)
Location: kernel/livepatch/core.c:998
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
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
In kernel/livepatch/core.c (c0000000001f0934)
Location: kernel/livepatch/core.c:904
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
In kernel/livepatch/core.c (ffffffff81124c0b)
Location: kernel/livepatch/core.c:904
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
In kernel/livepatch/core.c (ffffffff8111766b)
Location: kernel/livepatch/core.c:904
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
In kernel/livepatch/core.c (ffffffff81122afb)
Location: kernel/livepatch/core.c:904
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
In kernel/livepatch/core.c (ffffffff8112f10b)
Location: kernel/livepatch/core.c:904
Inline: True
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
