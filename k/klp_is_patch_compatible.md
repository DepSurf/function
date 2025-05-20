# Function: <code>klp_is_patch_compatible</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool klp_is_patch_compatible(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/state.c (ffffffff8113c0e0)
Location: kernel/livepatch/state.c:106
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff8113c0e0-ffffffff8113c15a: klp_is_patch_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool klp_is_patch_compatible(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/state.c (ffffffff811367f0)
Location: kernel/livepatch/state.c:106
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff811367f0-ffffffff8113686a: klp_is_patch_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool klp_is_patch_compatible(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/state.c (ffffffff811375e0)
Location: kernel/livepatch/state.c:106
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff811375e0-ffffffff8113765a: klp_is_patch_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool klp_is_patch_compatible(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/state.c (0)
Location: kernel/livepatch/state.c:106
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff81caffbd-ffffffff81caffd2: klp_is_patch_compatible.cold (STB_LOCAL)
ffffffff8115a2b0-ffffffff8115a35e: klp_is_patch_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool klp_is_patch_compatible(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/state.c (0)
Location: kernel/livepatch/state.c:106
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff81e60bcd-ffffffff81e60be2: klp_is_patch_compatible.cold (STB_LOCAL)
ffffffff81183a90-ffffffff81183b61: klp_is_patch_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool klp_is_patch_compatible(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/state.c (0)
Location: kernel/livepatch/state.c:106
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff8205a672-ffffffff8205a687: klp_is_patch_compatible.cold (STB_LOCAL)
ffffffff811bec90-ffffffff811bed61: klp_is_patch_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool klp_is_patch_compatible(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/state.c (0)
Location: kernel/livepatch/state.c:106
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff820d8ee6-ffffffff820d8efb: klp_is_patch_compatible.cold (STB_LOCAL)
ffffffff811d16c0-ffffffff811d1791: klp_is_patch_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool klp_is_patch_compatible(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/state.c (0)
Location: kernel/livepatch/state.c:106
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff821b461f-ffffffff821b4634: klp_is_patch_compatible.cold (STB_LOCAL)
ffffffff811e6340-ffffffff811e6411: klp_is_patch_compatible (STB_GLOBAL)
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
