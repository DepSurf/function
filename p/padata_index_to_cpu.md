# Function: <code>padata_index_to_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int padata_index_to_cpu(struct parallel_data *pd, int cpu_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff81189890)
Location: kernel/padata.c:36
Inline: False
Direct callers:
  - kernel/padata.c:padata_do_parallel
  - kernel/padata.c:padata_reorder
```
**Symbols:**

```
ffffffff81189890-ffffffff811898dd: padata_index_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int padata_index_to_cpu(struct parallel_data *pd, int cpu_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/padata.c (ffffffff8119bf70)
Location: kernel/padata.c:36
Inline: False
Direct callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
**Symbols:**

```
ffffffff8119bf70-ffffffff8119bfbd: padata_index_to_cpu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/padata.c (ffffffff811abca0)
Location: kernel/padata.c:37
Inline: True
Direct callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
**Symbols:**

```
ffffffff811abca0-ffffffff811abcf0: padata_index_to_cpu.isra.6 (STB_LOCAL)
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
In kernel/padata.c (ffffffff811b3100)
Location: kernel/padata.c:37
Inline: True
Direct callers:
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
**Symbols:**

```
ffffffff811b3100-ffffffff811b314e: padata_index_to_cpu.isra.6 (STB_LOCAL)
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
In kernel/padata.c (ffffffff811c6d50)
Location: kernel/padata.c:37
Inline: True
Direct callers:
  - kernel/padata.c:padata_reorder_timer
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
**Symbols:**

```
ffffffff811c6d50-ffffffff811c6d93: padata_index_to_cpu.isra.6 (STB_LOCAL)
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
In kernel/padata.c (ffffffff811e70c0)
Location: kernel/padata.c:38
Inline: True
Direct callers:
  - kernel/padata.c:padata_reorder_timer
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
**Symbols:**

```
ffffffff811e70c0-ffffffff811e7103: padata_index_to_cpu.isra.10 (STB_LOCAL)
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
In kernel/padata.c (ffffffff811f7cf0)
Location: kernel/padata.c:38
Inline: True
Direct callers:
  - kernel/padata.c:padata_reorder_timer
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
**Symbols:**

```
ffffffff811f7cf0-ffffffff811f7d33: padata_index_to_cpu.isra.11 (STB_LOCAL)
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
In kernel/padata.c (ffffffff8120fb70)
Location: kernel/padata.c:38
Inline: True
Direct callers:
  - kernel/padata.c:padata_reorder_timer
  - kernel/padata.c:padata_reorder
  - kernel/padata.c:padata_do_parallel
```
**Symbols:**

```
ffffffff8120fb70-ffffffff8120fbb8: padata_index_to_cpu.isra.0 (STB_LOCAL)
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
In kernel/padata.c (ffffffff8121d654)
Location: kernel/padata.c:40
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
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
In kernel/padata.c (ffffffff8124a79c)
Location: kernel/padata.c:63
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
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
In kernel/padata.c (ffffffff81254b4c)
Location: kernel/padata.c:63
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
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
In kernel/padata.c (ffffffff812590fb)
Location: kernel/padata.c:63
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
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
In kernel/padata.c (ffffffff81294ddb)
Location: kernel/padata.c:50
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
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
In kernel/padata.c (ffffffff812e9c19)
Location: kernel/padata.c:50
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
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
In kernel/padata.c (ffffffff81353a7e)
Location: kernel/padata.c:50
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
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
In kernel/padata.c (ffffffff81384c7e)
Location: kernel/padata.c:50
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
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
In kernel/padata.c (ffffffff813ae08e)
Location: kernel/padata.c:50
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_serial
```
</details>
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
In kernel/padata.c (ffff8000102aa130)
Location: kernel/padata.c:40
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
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
In kernel/padata.c (c04d81f4)
Location: kernel/padata.c:40
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
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
In kernel/padata.c (c00000000035c2c8)
Location: kernel/padata.c:40
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
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
In kernel/padata.c (ffffffe0001d2ff0)
Location: kernel/padata.c:40
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
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
In kernel/padata.c (ffffffff81215ca4)
Location: kernel/padata.c:40
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
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
In kernel/padata.c (ffffffff81208a04)
Location: kernel/padata.c:40
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
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
In kernel/padata.c (ffffffff81213a44)
Location: kernel/padata.c:40
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
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
In kernel/padata.c (ffffffff81222bc4)
Location: kernel/padata.c:40
Inline: True
Inline callers:
  - kernel/padata.c:padata_do_parallel
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
</ul>
