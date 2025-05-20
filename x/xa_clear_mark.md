# Function: <code>xa_clear_mark</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a19410)
Location: lib/xarray.c:1750
Inline: False
```
**Symbols:**

```
ffffffff81a19410-ffffffff81a19446: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a890e0)
Location: lib/xarray.c:1777
Inline: False
```
**Symbols:**

```
ffffffff81a890e0-ffffffff81a89118: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac0380)
Location: lib/xarray.c:1788
Inline: False
```
**Symbols:**

```
ffffffff81ac0380-ffffffff81ac03b8: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fb620)
Location: lib/xarray.c:1790
Inline: False
```
**Symbols:**

```
ffffffff815fb620-ffffffff815fb6b0: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81620190)
Location: lib/xarray.c:1980
Inline: False
```
**Symbols:**

```
ffffffff81620190-ffffffff81620220: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81603a00)
Location: lib/xarray.c:1981
Inline: False
```
**Symbols:**

```
ffffffff81603a00-ffffffff81603a90: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff816720b0)
Location: lib/xarray.c:1981
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
```
**Symbols:**

```
ffffffff816720b0-ffffffff81672144: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8178b700)
Location: lib/xarray.c:1988
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
```
**Symbols:**

```
ffffffff8178b700-ffffffff8178b73e: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff82049650)
Location: lib/xarray.c:1988
Inline: False
Direct callers:
  - net/core/devlink.c:devlink_unregister
  - net/core/devlink.c:devlink_unregister
```
**Symbols:**

```
ffffffff82049650-ffffffff8204968e: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff820c80b0)
Location: lib/xarray.c:1986
Inline: False
Direct callers:
  - net/devlink/core.c:devlink_unregister
```
**Symbols:**

```
ffffffff820c80b0-ffffffff820c80ee: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a2a30)
Location: lib/xarray.c:1992
Inline: False
Direct callers:
  - drivers/dpll/dpll_core.c:dpll_device_unregister
  - net/devlink/core.c:devl_unregister
  - net/devlink/core.c:devl_unregister
  - net/devlink/core.c:devlink_rel_nested_in_clear
```
**Symbols:**

```
ffffffff821a2a30-ffffffff821a2a6e: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d9b080)
Location: lib/xarray.c:1788
Inline: False
```
**Symbols:**

```
ffff800010d9b080-ffff800010d9b104: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e96ec0)
Location: lib/xarray.c:1788
Inline: False
```
**Symbols:**

```
c0e96ec0-c0e96f08: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000ee0470)
Location: lib/xarray.c:1788
Inline: False
```
**Symbols:**

```
c000000000ee0470-c000000000ee0528: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c34f6)
Location: lib/xarray.c:1788
Inline: False
```
**Symbols:**

```
ffffffe0008c34f6-ffffffe0008c356e: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5f1d0)
Location: lib/xarray.c:1788
Inline: False
```
**Symbols:**

```
ffffffff81a5f1d0-ffffffff81a5f208: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1c260)
Location: lib/xarray.c:1788
Inline: False
```
**Symbols:**

```
ffffffff81a1c260-ffffffff81a1c298: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81acb5c0)
Location: lib/xarray.c:1788
Inline: False
```
**Symbols:**

```
ffffffff81acb5c0-ffffffff81acb5f8: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xa_clear_mark(struct xarray *xa, long unsigned int index, xa_mark_t mark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad6700)
Location: lib/xarray.c:1788
Inline: False
```
**Symbols:**

```
ffffffff81ad6700-ffffffff81ad6736: xa_clear_mark (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
