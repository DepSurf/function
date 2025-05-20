# Function: <code>param_get_sample_interval</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_get_sample_interval(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (ffffffff8133bdab)
Location: mm/kfence/core.c:71
Inline: True
```
**Symbols:**

```
ffffffff8133bd70-ffffffff8133bdc7: param_get_sample_interval (STB_LOCAL)
ffffffff81cc1e7c-ffffffff81cc1e90: param_get_sample_interval.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_get_sample_interval(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (ffffffff813ae776)
Location: mm/kfence/core.c:85
Inline: True
```
**Symbols:**

```
ffffffff813ae730-ffffffff813ae796: param_get_sample_interval (STB_LOCAL)
ffffffff81e74386-ffffffff81e7439b: param_get_sample_interval.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_get_sample_interval(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (ffffffff8142ec16)
Location: mm/kfence/core.c:84
Inline: True
```
**Symbols:**

```
ffffffff8142ebd0-ffffffff8142ec36: param_get_sample_interval (STB_LOCAL)
ffffffff820678e6-ffffffff820678fb: param_get_sample_interval.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_get_sample_interval(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (ffffffff814643c6)
Location: mm/kfence/core.c:84
Inline: True
```
**Symbols:**

```
ffffffff81464380-ffffffff814643e6: param_get_sample_interval (STB_LOCAL)
ffffffff820e7206-ffffffff820e721b: param_get_sample_interval.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int param_get_sample_interval(char *buffer, const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (ffffffff81493746)
Location: mm/kfence/core.c:84
Inline: True
```
**Symbols:**

```
ffffffff81493700-ffffffff81493766: param_get_sample_interval (STB_LOCAL)
ffffffff821c3dbe-ffffffff821c3dd3: param_get_sample_interval.cold (STB_LOCAL)
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
