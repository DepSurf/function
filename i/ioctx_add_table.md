# Function: <code>ioctx_add_table</code>

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
In fs/aio.c (ffffffff8125d025)
Location: fs/aio.c:622
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_setup
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
In fs/aio.c (ffffffff81285df9)
Location: fs/aio.c:632
Inline: True
Inline callers:
  - fs/aio.c:SyS_io_setup
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
In fs/aio.c (ffffffff81299e5b)
Location: fs/aio.c:635
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
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
In fs/aio.c (ffffffff812a7bb0)
Location: fs/aio.c:634
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
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
In fs/aio.c (ffffffff812cb140)
Location: fs/aio.c:657
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
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
In fs/aio.c (ffffffff812f560a)
Location: fs/aio.c:620
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
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
In fs/aio.c (ffffffff8130a6fa)
Location: fs/aio.c:636
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
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
In fs/aio.c (ffffffff8132c91c)
Location: fs/aio.c:633
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
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
In fs/aio.c (ffffffff8133f76c)
Location: fs/aio.c:633
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ioctx_add_table(struct kioctx *ctx, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813770e0)
Location: fs/aio.c:633
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff813770e0-ffffffff81377261: ioctx_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ioctx_add_table(struct kioctx *ctx, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81384ce0)
Location: fs/aio.c:635
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81384ce0-ffffffff81384e5e: ioctx_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ioctx_add_table(struct kioctx *ctx, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8138ba90)
Location: fs/aio.c:632
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff8138ba90-ffffffff8138bc0e: ioctx_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ioctx_add_table(struct kioctx *ctx, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff813d9040)
Location: fs/aio.c:633
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff813d9040-ffffffff813d91be: ioctx_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ioctx_add_table(struct kioctx *ctx, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814619b0)
Location: fs/aio.c:660
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff814619b0-ffffffff81461b5d: ioctx_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ioctx_add_table(struct kioctx *ctx, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814f1b40)
Location: fs/aio.c:664
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff814f1b40-ffffffff814f1ced: ioctx_add_table (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ioctx_add_table(struct kioctx *ctx, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/aio.c (0)
Location: fs/aio.c:663
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff81528080-ffffffff815282a5: ioctx_add_table (STB_LOCAL)
ffffffff820e9fe9-ffffffff820ea026: ioctx_add_table.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ioctx_add_table(struct kioctx *ctx, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff8155d170)
Location: fs/aio.c:673
Inline: False
Direct callers:
  - fs/aio.c:ioctx_alloc
```
**Symbols:**

```
ffffffff8155d170-ffffffff8155d32a: ioctx_add_table (STB_LOCAL)
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
In fs/aio.c (ffff8000103fedbc)
Location: fs/aio.c:633
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
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
In fs/aio.c (c05d0d94)
Location: fs/aio.c:633
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_setup
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
In fs/aio.c (c000000000508864)
Location: fs/aio.c:633
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
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
In fs/aio.c (ffffffe0002abddc)
Location: fs/aio.c:633
Inline: True
Inline callers:
  - fs/aio.c:__se_sys_io_setup
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
In fs/aio.c (ffffffff81337d4c)
Location: fs/aio.c:633
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
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
In fs/aio.c (ffffffff81328a7c)
Location: fs/aio.c:633
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
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
In fs/aio.c (ffffffff8133581c)
Location: fs/aio.c:633
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
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
In fs/aio.c (ffffffff81348850)
Location: fs/aio.c:633
Inline: True
Inline callers:
  - fs/aio.c:ioctx_alloc
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
