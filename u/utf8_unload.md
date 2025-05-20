# Function: <code>utf8_unload</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void utf8_unload(struct unicode_map *um);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81405160)
Location: fs/unicode/utf8-core.c:209
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff81405160-ffffffff81405170: utf8_unload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void utf8_unload(struct unicode_map *um);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8141f090)
Location: fs/unicode/utf8-core.c:209
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8141f090-ffffffff8141f0a0: utf8_unload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void utf8_unload(struct unicode_map *um);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8146db60)
Location: fs/unicode/utf8-core.c:209
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8146db60-ffffffff8146db70: utf8_unload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void utf8_unload(struct unicode_map *um);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81488310)
Location: fs/unicode/utf8-core.c:230
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff81488310-ffffffff81488320: utf8_unload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void utf8_unload(struct unicode_map *um);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8148dcf0)
Location: fs/unicode/utf8-core.c:230
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8148dcf0-ffffffff8148dd00: utf8_unload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void utf8_unload(struct unicode_map *um);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff814e5760)
Location: fs/unicode/utf8-core.c:230
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff814e5760-ffffffff814e5770: utf8_unload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void utf8_unload(struct unicode_map *um);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81573810)
Location: fs/unicode/utf8-core.c:208
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff81573810-ffffffff81573849: utf8_unload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void utf8_unload(struct unicode_map *um);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81618e20)
Location: fs/unicode/utf8-core.c:208
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff81618e20-ffffffff81618e59: utf8_unload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void utf8_unload(struct unicode_map *um);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81650ee0)
Location: fs/unicode/utf8-core.c:208
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff81650ee0-ffffffff81650f19: utf8_unload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void utf8_unload(struct unicode_map *um);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8168a4c0)
Location: fs/unicode/utf8-core.c:208
Inline: True
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8168a4c0-ffffffff8168a4f9: utf8_unload (STB_GLOBAL)
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
void utf8_unload(struct unicode_map *um);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffff8000105012e0)
Location: fs/unicode/utf8-core.c:209
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffff8000105012e0-ffff80001050130c: utf8_unload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void utf8_unload(struct unicode_map *um);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (c06bdfa4)
Location: fs/unicode/utf8-core.c:209
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
c06bdfa4-c06bdfc0: utf8_unload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void utf8_unload(struct unicode_map *um);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (c0000000006454a0)
Location: fs/unicode/utf8-core.c:209
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
c0000000006454a0-c0000000006454d4: utf8_unload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void utf8_unload(struct unicode_map *um);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffe00036e954)
Location: fs/unicode/utf8-core.c:209
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffe00036e954-ffffffe00036e97e: utf8_unload (STB_GLOBAL)
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
void utf8_unload(struct unicode_map *um);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81417670)
Location: fs/unicode/utf8-core.c:209
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff81417670-ffffffff81417680: utf8_unload (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void utf8_unload(struct unicode_map *um);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff814080f0)
Location: fs/unicode/utf8-core.c:209
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff814080f0-ffffffff81408100: utf8_unload (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void utf8_unload(struct unicode_map *um);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8142a650)
Location: fs/unicode/utf8-core.c:209
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_put_super
```
**Symbols:**

```
ffffffff8142a650-ffffffff8142a660: utf8_unload (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
