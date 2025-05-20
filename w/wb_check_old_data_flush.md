# Function: <code>wb_check_old_data_flush</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8123c753)
Location: fs/fs-writeback.c:1786
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8126476a)
Location: fs/fs-writeback.c:1834
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81277baa)
Location: fs/fs-writeback.c:1832
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81284e93)
Location: fs/fs-writeback.c:1846
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a7922)
Location: fs/fs-writeback.c:1838
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812ce53e)
Location: fs/fs-writeback.c:1839
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812e383e)
Location: fs/fs-writeback.c:1865
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (ffffffff81301fa9)
Location: fs/fs-writeback.c:1880
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (ffffffff813150a9)
Location: fs/fs-writeback.c:1968
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int wb_check_old_data_flush(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134daf0)
Location: fs/fs-writeback.c:1976
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_do_writeback
```
**Symbols:**

```
ffffffff8134daf0-ffffffff8134dbae: wb_check_old_data_flush (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int wb_check_old_data_flush(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135a990)
Location: fs/fs-writeback.c:1972
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_do_writeback
```
**Symbols:**

```
ffffffff8135a990-ffffffff8135aa4e: wb_check_old_data_flush (STB_LOCAL)
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
In fs/fs-writeback.c (ffffffff813615e0)
Location: fs/fs-writeback.c:1987
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
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
In fs/fs-writeback.c (ffffffff813afc40)
Location: fs/fs-writeback.c:2127
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
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
In fs/fs-writeback.c (ffffffff814347c0)
Location: fs/fs-writeback.c:2113
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
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
In fs/fs-writeback.c (ffffffff814c27a0)
Location: fs/fs-writeback.c:2137
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
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
In fs/fs-writeback.c (ffffffff814f7b60)
Location: fs/fs-writeback.c:2148
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
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
In fs/fs-writeback.c (ffffffff8152c2b0)
Location: fs/fs-writeback.c:2170
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_do_writeback
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
In fs/fs-writeback.c (ffff8000103cb2d4)
Location: fs/fs-writeback.c:1968
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (c05a762c)
Location: fs/fs-writeback.c:1968
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (c0000000004cce50)
Location: fs/fs-writeback.c:1968
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (ffffffe0002890a2)
Location: fs/fs-writeback.c:1968
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (ffffffff8130d689)
Location: fs/fs-writeback.c:1968
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (ffffffff812fe299)
Location: fs/fs-writeback.c:1968
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (ffffffff8130b479)
Location: fs/fs-writeback.c:1968
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
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
In fs/fs-writeback.c (ffffffff8131cc39)
Location: fs/fs-writeback.c:1968
Inline: True
Inline callers:
  - fs/fs-writeback.c:wb_workfn
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
