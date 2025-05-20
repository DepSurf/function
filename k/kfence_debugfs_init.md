# Function: <code>kfence_debugfs_init</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int kfence_debugfs_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff832dcce6)
Location: mm/kfence/core.c:584
Inline: False
```
**Symbols:**

```
ffffffff832dcce6-ffffffff832dcd42: kfence_debugfs_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kfence_debugfs_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff834925b2)
Location: mm/kfence/core.c:741
Inline: False
```
**Symbols:**

```
ffffffff834925b2-ffffffff8349261b: kfence_debugfs_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kfence_debugfs_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff83ec6220)
Location: mm/kfence/core.c:729
Inline: False
```
**Symbols:**

```
ffffffff83ec6220-ffffffff83ec628c: kfence_debugfs_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kfence_debugfs_init();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (ffffffff8146441f)
Location: mm/kfence/core.c:757
Inline: True
Direct callers:
  - mm/kfence/core.c:param_set_sample_interval
```
**Symbols:**

```
ffffffff81464400-ffffffff81464481: kfence_debugfs_init (STB_LOCAL)
ffffffff820e721b-ffffffff820e722f: kfence_debugfs_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kfence_debugfs_init();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (ffffffff8149379f)
Location: mm/kfence/core.c:752
Inline: True
Direct callers:
  - mm/kfence/core.c:kfence_init_late
```
**Symbols:**

```
ffffffff81493780-ffffffff81493801: kfence_debugfs_init (STB_LOCAL)
ffffffff821c3dd3-ffffffff821c3de7: kfence_debugfs_init.cold (STB_LOCAL)
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
