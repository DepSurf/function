# Function: <code>kfence_init_pool</code>

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
bool kfence_init_pool();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff832dcd42)
Location: mm/kfence/core.c:428
Inline: False
Direct callers:
  - mm/kfence/core.c:kfence_init
```
**Symbols:**

```
ffffffff832dcd42-ffffffff832dcf55: kfence_init_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int kfence_init_pool();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff813aeeb0)
Location: mm/kfence/core.c:540
Inline: False
Direct callers:
  - mm/kfence/core.c:param_set_sample_interval
  - mm/kfence/core.c:kfence_init
```
**Symbols:**

```
ffffffff813aeeb0-ffffffff813af164: kfence_init_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int kfence_init_pool();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff8142f410)
Location: mm/kfence/core.c:539
Inline: False
Direct callers:
  - mm/kfence/core.c:param_set_sample_interval
  - mm/kfence/core.c:kfence_init
```
**Symbols:**

```
ffffffff8142f410-ffffffff8142f6bb: kfence_init_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int kfence_init_pool();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff814645f0)
Location: mm/kfence/core.c:567
Inline: False
Direct callers:
  - mm/kfence/core.c:param_set_sample_interval
  - mm/kfence/core.c:kfence_init
```
**Symbols:**

```
ffffffff814645f0-ffffffff814648de: kfence_init_pool (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int kfence_init_pool();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (ffffffff81493db0)
Location: mm/kfence/core.c:571
Inline: True
Direct callers:
  - mm/kfence/core.c:kfence_init_late
  - mm/kfence/core.c:kfence_init
```
**Symbols:**

```
ffffffff81493db0-ffffffff8149401d: kfence_init_pool.part.0 (STB_LOCAL)
ffffffff81494030-ffffffff814940e0: kfence_init_pool (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>long unsigned int</code>
</li>
</ul>
</details>
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
