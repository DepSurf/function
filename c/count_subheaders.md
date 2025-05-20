# Function: <code>count_subheaders</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int count_subheaders(struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81283fc0)
Location: fs/proc/proc_sysctl.c:1310
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:count_subheaders
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff81283fc0-ffffffff81284028: count_subheaders (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int count_subheaders(struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812b1070)
Location: fs/proc/proc_sysctl.c:1316
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:count_subheaders
```
**Symbols:**

```
ffffffff812b1070-ffffffff812b10d8: count_subheaders (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int count_subheaders(struct ctl_table *table);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812c6900)
Location: fs/proc/proc_sysctl.c:1322
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
  - fs/proc/proc_sysctl.c:count_subheaders
```
**Symbols:**

```
ffffffff812c6900-ffffffff812c6968: count_subheaders (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff812d5e7b)
Location: fs/proc/proc_sysctl.c:1386
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff812d3fd0-ffffffff812d4029: count_subheaders.part.12 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff812fa6bb)
Location: fs/proc/proc_sysctl.c:1387
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff812f8800-ffffffff812f8859: count_subheaders.part.12 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff8132675f)
Location: fs/proc/proc_sysctl.c:1389
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff81325830-ffffffff8132588b: count_subheaders.part.15 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff8133da4f)
Location: fs/proc/proc_sysctl.c:1388
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff8133cbf0-ffffffff8133cc4b: count_subheaders.part.17 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff81365930)
Location: fs/proc/proc_sysctl.c:1413
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff81364e80-ffffffff81364edb: count_subheaders.part.0 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff8137dbc0)
Location: fs/proc/proc_sysctl.c:1413
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff8137d110-ffffffff8137d16b: count_subheaders.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c906f)
Location: fs/proc/proc_sysctl.c:1396
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff813c6ca0-ffffffff813c6e94: count_subheaders.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813db05f)
Location: fs/proc/proc_sysctl.c:1396
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff813d8c70-ffffffff813d8e64: count_subheaders.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813e1f8f)
Location: fs/proc/proc_sysctl.c:1400
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff813dfb40-ffffffff813dfd13: count_subheaders.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81433a9f)
Location: fs/proc/proc_sysctl.c:1400
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff814314d0-ffffffff814316a3: count_subheaders.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814ada0e)
Location: fs/proc/proc_sysctl.c:1458
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff814ab720-ffffffff814ab96b: count_subheaders.part.0 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff81543f0e)
Location: fs/proc/proc_sysctl.c:1457
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff81541780-ffffffff815419cb: count_subheaders.part.0 (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffff80001044ad54)
Location: fs/proc/proc_sysctl.c:1413
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffff800010449ba0-ffff800010449c24: count_subheaders.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (c060fb9c)
Location: fs/proc/proc_sysctl.c:1413
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
c060ef0c-c060ef78: count_subheaders.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (c000000000561648)
Location: fs/proc/proc_sysctl.c:1413
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
c000000000560e90-c000000000560f58: count_subheaders.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffe0002e0436)
Location: fs/proc/proc_sysctl.c:1413
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffe0002df1ea-ffffffe0002df246: count_subheaders.part.0 (STB_LOCAL)
```
</details>
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
In fs/proc/proc_sysctl.c (ffffffff813761a0)
Location: fs/proc/proc_sysctl.c:1413
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff813756f0-ffffffff8137574b: count_subheaders.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81366c70)
Location: fs/proc/proc_sysctl.c:1413
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff813661c0-ffffffff8136621b: count_subheaders.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81373c70)
Location: fs/proc/proc_sysctl.c:1413
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff813731c0-ffffffff8137321b: count_subheaders.part.0 (STB_LOCAL)
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
In fs/proc/proc_sysctl.c (ffffffff8138720a)
Location: fs/proc/proc_sysctl.c:1413
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
Direct callers:
  - fs/proc/proc_sysctl.c:unregister_sysctl_table
  - fs/proc/proc_sysctl.c:__register_sysctl_paths
```
**Symbols:**

```
ffffffff81386de0-ffffffff81386e3b: count_subheaders.part.0 (STB_LOCAL)
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
</ul>
