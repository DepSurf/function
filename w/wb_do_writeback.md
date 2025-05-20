# Function: <code>wb_do_writeback</code>

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
In fs/fs-writeback.c (ffffffff8123c639)
Location: fs/fs-writeback.c:1823
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
In fs/fs-writeback.c (ffffffff81264659)
Location: fs/fs-writeback.c:1871
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
In fs/fs-writeback.c (ffffffff81277a99)
Location: fs/fs-writeback.c:1869
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
In fs/fs-writeback.c (ffffffff81284e23)
Location: fs/fs-writeback.c:1883
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
In fs/fs-writeback.c (ffffffff812a78a3)
Location: fs/fs-writeback.c:1899
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
In fs/fs-writeback.c (ffffffff812ce44a)
Location: fs/fs-writeback.c:1900
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
In fs/fs-writeback.c (ffffffff812e374a)
Location: fs/fs-writeback.c:1926
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
In fs/fs-writeback.c (ffffffff81301e89)
Location: fs/fs-writeback.c:1941
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
In fs/fs-writeback.c (ffffffff81314f8c)
Location: fs/fs-writeback.c:2029
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
long int wb_do_writeback(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134dbb0)
Location: fs/fs-writeback.c:2037
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
```
**Symbols:**

```
ffffffff8134dbb0-ffffffff8134dd2b: wb_do_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int wb_do_writeback(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8135aa50)
Location: fs/fs-writeback.c:2033
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
```
**Symbols:**

```
ffffffff8135aa50-ffffffff8135abaf: wb_do_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int wb_do_writeback(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81361530)
Location: fs/fs-writeback.c:2048
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
```
**Symbols:**

```
ffffffff81361530-ffffffff813617a4: wb_do_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int wb_do_writeback(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813afb90)
Location: fs/fs-writeback.c:2188
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
```
**Symbols:**

```
ffffffff813afb90-ffffffff813afe04: wb_do_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int wb_do_writeback(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81434710)
Location: fs/fs-writeback.c:2174
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
```
**Symbols:**

```
ffffffff81434710-ffffffff814349ad: wb_do_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int wb_do_writeback(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814c26f0)
Location: fs/fs-writeback.c:2198
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
```
**Symbols:**

```
ffffffff814c26f0-ffffffff814c298d: wb_do_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int wb_do_writeback(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f7ab0)
Location: fs/fs-writeback.c:2209
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
```
**Symbols:**

```
ffffffff814f7ab0-ffffffff814f7d4d: wb_do_writeback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int wb_do_writeback(struct bdi_writeback *wb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8152c200)
Location: fs/fs-writeback.c:2231
Inline: False
Direct callers:
  - fs/fs-writeback.c:wb_workfn
```
**Symbols:**

```
ffffffff8152c200-ffffffff8152c49d: wb_do_writeback (STB_LOCAL)
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
In fs/fs-writeback.c (ffff8000103cb128)
Location: fs/fs-writeback.c:2029
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
In fs/fs-writeback.c (c05a7550)
Location: fs/fs-writeback.c:2029
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
In fs/fs-writeback.c (c0000000004ccce0)
Location: fs/fs-writeback.c:2029
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
Location: fs/fs-writeback.c:2029
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
In fs/fs-writeback.c (ffffffff8130d56c)
Location: fs/fs-writeback.c:2029
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
In fs/fs-writeback.c (ffffffff812fe17c)
Location: fs/fs-writeback.c:2029
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
In fs/fs-writeback.c (ffffffff8130b35c)
Location: fs/fs-writeback.c:2029
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
In fs/fs-writeback.c (ffffffff8131cb1c)
Location: fs/fs-writeback.c:2029
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
