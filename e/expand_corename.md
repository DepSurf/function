# Function: <code>expand_corename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int expand_corename(struct core_name *cn, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8126ec20)
Location: fs/coredump.c:58
Inline: False
Direct callers:
  - fs/coredump.c:cn_vprintf
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8126ec20-ffffffff8126ec7c: expand_corename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int expand_corename(struct core_name *cn, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8129a390)
Location: fs/coredump.c:62
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:cn_vprintf
```
**Symbols:**

```
ffffffff8129a390-ffffffff8129a3ec: expand_corename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int expand_corename(struct core_name *cn, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff812aef20)
Location: fs/coredump.c:63
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:cn_vprintf
```
**Symbols:**

```
ffffffff812aef20-ffffffff812aef7c: expand_corename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int expand_corename(struct core_name *cn, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff812bc360)
Location: fs/coredump.c:65
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:cn_vprintf
```
**Symbols:**

```
ffffffff812bc360-ffffffff812bc3bc: expand_corename (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int expand_corename(struct core_name *cn, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff812dfc50)
Location: fs/coredump.c:66
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:cn_vprintf
```
**Symbols:**

```
ffffffff812dfc50-ffffffff812dfcac: expand_corename (STB_LOCAL)
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
In fs/coredump.c (ffffffff8130bf40)
Location: fs/coredump.c:66
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:cn_vprintf
```
**Symbols:**

```
ffffffff8130bf40-ffffffff8130bfa4: expand_corename.isra.10 (STB_LOCAL)
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
In fs/coredump.c (ffffffff813217a0)
Location: fs/coredump.c:66
Inline: True
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/coredump.c:cn_vprintf
```
**Symbols:**

```
ffffffff813217a0-ffffffff81321804: expand_corename.isra.10 (STB_LOCAL)
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
In fs/coredump.c (ffffffff81349040)
Location: fs/coredump.c:67
Inline: True
Direct callers:
  - fs/coredump.c:cn_vprintf
```
**Symbols:**

```
ffffffff81349040-ffffffff813490a4: expand_corename.isra.0 (STB_LOCAL)
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
In fs/coredump.c (ffffffff813612e0)
Location: fs/coredump.c:67
Inline: True
Direct callers:
  - fs/coredump.c:cn_vprintf
```
**Symbols:**

```
ffffffff813612e0-ffffffff81361344: expand_corename.isra.0 (STB_LOCAL)
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
In fs/coredump.c (ffffffff813a7676)
Location: fs/coredump.c:67
Inline: True
Inline callers:
  - fs/coredump.c:format_corename
  - fs/coredump.c:cn_vprintf
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
In fs/coredump.c (ffffffff813b84d6)
Location: fs/coredump.c:67
Inline: True
Inline callers:
  - fs/coredump.c:format_corename
  - fs/coredump.c:cn_vprintf
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
In fs/coredump.c (ffffffff813bf199)
Location: fs/coredump.c:67
Inline: True
Inline callers:
  - fs/coredump.c:cn_vprintf
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
In fs/coredump.c (ffffffff8140efc9)
Location: fs/coredump.c:67
Inline: True
Inline callers:
  - fs/coredump.c:cn_vprintf
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
In fs/coredump.c (ffffffff81484bd9)
Location: fs/coredump.c:69
Inline: True
Inline callers:
  - fs/coredump.c:cn_vprintf
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
In fs/coredump.c (ffffffff815180f5)
Location: fs/coredump.c:69
Inline: True
Inline callers:
  - fs/coredump.c:cn_vprintf
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
In fs/coredump.c (ffffffff8154fa05)
Location: fs/coredump.c:69
Inline: True
Inline callers:
  - fs/coredump.c:cn_vprintf
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
In fs/coredump.c (ffffffff81585835)
Location: fs/coredump.c:69
Inline: True
Inline callers:
  - fs/coredump.c:cn_vprintf
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
In fs/coredump.c (ffff8000104278b8)
Location: fs/coredump.c:67
Inline: True
Direct callers:
  - fs/coredump.c:cn_vprintf
```
**Symbols:**

```
ffff8000104278b8-ffff800010427938: expand_corename.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int expand_corename(struct core_name *cn, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (c05f0364)
Location: fs/coredump.c:67
Inline: False
Direct callers:
  - fs/coredump.c:format_corename
  - fs/coredump.c:cn_vprintf
```
**Symbols:**

```
c05f0364-c05f03cc: expand_corename (STB_LOCAL)
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
In fs/coredump.c (c000000000537650)
Location: fs/coredump.c:67
Inline: True
Direct callers:
  - fs/coredump.c:cn_vprintf
```
**Symbols:**

```
c000000000537650-c000000000537700: expand_corename.isra.0 (STB_LOCAL)
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
In fs/coredump.c (ffffffe0002c5dae)
Location: fs/coredump.c:67
Inline: True
Direct callers:
  - fs/coredump.c:cn_vprintf
```
**Symbols:**

```
ffffffe0002c5dae-ffffffe0002c5e22: expand_corename.isra.0 (STB_LOCAL)
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
In fs/coredump.c (ffffffff813598c0)
Location: fs/coredump.c:67
Inline: True
Direct callers:
  - fs/coredump.c:cn_vprintf
```
**Symbols:**

```
ffffffff813598c0-ffffffff81359924: expand_corename.isra.0 (STB_LOCAL)
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
In fs/coredump.c (ffffffff8134a570)
Location: fs/coredump.c:67
Inline: True
Direct callers:
  - fs/coredump.c:cn_vprintf
```
**Symbols:**

```
ffffffff8134a570-ffffffff8134a5d4: expand_corename.isra.0 (STB_LOCAL)
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
In fs/coredump.c (ffffffff81357390)
Location: fs/coredump.c:67
Inline: True
Direct callers:
  - fs/coredump.c:cn_vprintf
```
**Symbols:**

```
ffffffff81357390-ffffffff813573f4: expand_corename.isra.0 (STB_LOCAL)
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
In fs/coredump.c (ffffffff8136aa70)
Location: fs/coredump.c:67
Inline: True
Direct callers:
  - fs/coredump.c:cn_vprintf
```
**Symbols:**

```
ffffffff8136aa70-ffffffff8136aad4: expand_corename.isra.0 (STB_LOCAL)
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
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
