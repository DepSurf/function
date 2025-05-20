# Function: <code>wb_check_start_all</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff812a7913)
Location: fs/fs-writeback.c:1872
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
In fs/fs-writeback.c (ffffffff812ce4ba)
Location: fs/fs-writeback.c:1873
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
In fs/fs-writeback.c (ffffffff812e37ba)
Location: fs/fs-writeback.c:1899
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
In fs/fs-writeback.c (ffffffff81301ef8)
Location: fs/fs-writeback.c:1914
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
In fs/fs-writeback.c (ffffffff81314ff8)
Location: fs/fs-writeback.c:2002
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
long int wb_check_start_all(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134da10)
Location: fs/fs-writeback.c:2010
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_do_writeback
```
**Symbols:**

```
ffffffff8134da10-ffffffff8134dae7: wb_check_start_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int wb_check_start_all(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135a8b0)
Location: fs/fs-writeback.c:2006
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_do_writeback
```
**Symbols:**

```
ffffffff8135a8b0-ffffffff8135a987: wb_check_start_all (STB_LOCAL)
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
In fs/fs-writeback.c (ffffffff813615d4)
Location: fs/fs-writeback.c:2021
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
In fs/fs-writeback.c (ffffffff813afc34)
Location: fs/fs-writeback.c:2161
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
In fs/fs-writeback.c (ffffffff814347b4)
Location: fs/fs-writeback.c:2147
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
In fs/fs-writeback.c (ffffffff814c2794)
Location: fs/fs-writeback.c:2171
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
In fs/fs-writeback.c (ffffffff814f7b54)
Location: fs/fs-writeback.c:2182
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
In fs/fs-writeback.c (ffffffff8152c2a4)
Location: fs/fs-writeback.c:2204
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
In fs/fs-writeback.c (ffff8000103cb21c)
Location: fs/fs-writeback.c:2002
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
In fs/fs-writeback.c (c05a75f0)
Location: fs/fs-writeback.c:2002
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
In fs/fs-writeback.c (c0000000004ccd78)
Location: fs/fs-writeback.c:2002
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
In fs/fs-writeback.c (ffffffe000289082)
Location: fs/fs-writeback.c:2002
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
In fs/fs-writeback.c (ffffffff8130d5d8)
Location: fs/fs-writeback.c:2002
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
In fs/fs-writeback.c (ffffffff812fe1e8)
Location: fs/fs-writeback.c:2002
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
In fs/fs-writeback.c (ffffffff8130b3c8)
Location: fs/fs-writeback.c:2002
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
In fs/fs-writeback.c (ffffffff8131cb88)
Location: fs/fs-writeback.c:2002
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
