# Function: <code>format_corename</code>

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
In fs/coredump.c (ffffffff8126f350)
Location: fs/coredump.c:162
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff8129ab54)
Location: fs/coredump.c:186
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff812af713)
Location: fs/coredump.c:187
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff812bcb68)
Location: fs/coredump.c:189
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff812e0453)
Location: fs/coredump.c:190
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff8130c68e)
Location: fs/coredump.c:190
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff81321eee)
Location: fs/coredump.c:190
Inline: True
Inline callers:
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff813493c0)
Location: fs/coredump.c:191
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff813493c0-ffffffff81349927: format_corename.isra.0 (STB_LOCAL)
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
In fs/coredump.c (ffffffff81361660)
Location: fs/coredump.c:191
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81361660-ffffffff81361bc7: format_corename.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int format_corename(struct core_name *cn, struct coredump_params *cprm, size_t **argv, int *argc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813a7610)
Location: fs/coredump.c:191
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff813a7610-ffffffff813a7abe: format_corename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int format_corename(struct core_name *cn, struct coredump_params *cprm, size_t **argv, int *argc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813b8470)
Location: fs/coredump.c:196
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff813b8470-ffffffff813b895f: format_corename (STB_LOCAL)
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
In fs/coredump.c (ffffffff813bf4b0)
Location: fs/coredump.c:196
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff813bf4b0-ffffffff813bf99f: format_corename.constprop.0 (STB_LOCAL)
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
In fs/coredump.c (ffffffff8140f2e0)
Location: fs/coredump.c:196
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8140f2e0-ffffffff8140f7cf: format_corename.constprop.0 (STB_LOCAL)
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
In fs/coredump.c (ffffffff81484f50)
Location: fs/coredump.c:198
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81484f50-ffffffff81485449: format_corename.constprop.0 (STB_LOCAL)
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
In fs/coredump.c (ffffffff815184c0)
Location: fs/coredump.c:201
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff815184c0-ffffffff815189f2: format_corename.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/coredump.c (ffffffff8154fdd0)
Location: fs/coredump.c:201
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8154fdd0-ffffffff81550300: format_corename.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/coredump.c (ffffffff81585c30)
Location: fs/coredump.c:201
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81585c30-ffffffff8158618f: format_corename.constprop.0 (STB_LOCAL)
```
</details>
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
In fs/coredump.c (ffff800010427d70)
Location: fs/coredump.c:191
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffff800010427d70-ffff800010428304: format_corename.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int format_corename(struct core_name *cn, struct coredump_params *cprm, size_t **argv, int *argc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (c05f0890)
Location: fs/coredump.c:191
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
c05f0890-c05f0f70: format_corename (STB_LOCAL)
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
In fs/coredump.c (c000000000537b90)
Location: fs/coredump.c:191
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
c000000000537b90-c00000000053842c: format_corename.isra.0 (STB_LOCAL)
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
In fs/coredump.c (ffffffe0002c60fc)
Location: fs/coredump.c:191
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffe0002c60fc-ffffffe0002c658c: format_corename.isra.0 (STB_LOCAL)
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
In fs/coredump.c (ffffffff81359c40)
Location: fs/coredump.c:191
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81359c40-ffffffff8135a1a7: format_corename.isra.0 (STB_LOCAL)
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
In fs/coredump.c (ffffffff8134a8f0)
Location: fs/coredump.c:191
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8134a8f0-ffffffff8134ae57: format_corename.isra.0 (STB_LOCAL)
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
In fs/coredump.c (ffffffff81357710)
Location: fs/coredump.c:191
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81357710-ffffffff81357c77: format_corename.isra.0 (STB_LOCAL)
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
In fs/coredump.c (ffffffff8136adf0)
Location: fs/coredump.c:191
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8136adf0-ffffffff8136b357: format_corename.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
