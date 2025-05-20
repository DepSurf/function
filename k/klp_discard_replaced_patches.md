# Function: <code>klp_discard_replaced_patches</code>

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
void klp_discard_replaced_patches(struct klp_patch *new_patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81120240)
Location: kernel/livepatch/core.c:1038
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_complete_transition
```
**Symbols:**

```
ffffffff81120240-ffffffff811202c6: klp_discard_replaced_patches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void klp_discard_replaced_patches(struct klp_patch *new_patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112c960)
Location: kernel/livepatch/core.c:1038
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_complete_transition
```
**Symbols:**

```
ffffffff8112c960-ffffffff8112c9e6: klp_discard_replaced_patches (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void klp_discard_replaced_patches(struct klp_patch *new_patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (c0000000001f10c0)
Location: kernel/livepatch/core.c:1038
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_complete_transition
```
**Symbols:**

```
c0000000001f10c0-c0000000001f11bc: klp_discard_replaced_patches (STB_GLOBAL)
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
void klp_discard_replaced_patches(struct klp_patch *new_patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81124f40)
Location: kernel/livepatch/core.c:1038
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_complete_transition
```
**Symbols:**

```
ffffffff81124f40-ffffffff81124fc6: klp_discard_replaced_patches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void klp_discard_replaced_patches(struct klp_patch *new_patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811179a0)
Location: kernel/livepatch/core.c:1038
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_complete_transition
```
**Symbols:**

```
ffffffff811179a0-ffffffff81117a26: klp_discard_replaced_patches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void klp_discard_replaced_patches(struct klp_patch *new_patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81122e30)
Location: kernel/livepatch/core.c:1038
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_complete_transition
```
**Symbols:**

```
ffffffff81122e30-ffffffff81122eb6: klp_discard_replaced_patches (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void klp_discard_replaced_patches(struct klp_patch *new_patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112f440)
Location: kernel/livepatch/core.c:1038
Inline: False
Direct callers:
  - kernel/livepatch/transition.c:klp_complete_transition
```
**Symbols:**

```
ffffffff8112f440-ffffffff8112f4c6: klp_discard_replaced_patches (STB_GLOBAL)
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
