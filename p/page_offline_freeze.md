# Function: <code>page_offline_freeze</code>

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
void page_offline_freeze();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812c15c0)
Location: mm/util.c:1063
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff812c15c0-ffffffff812c15d7: page_offline_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void page_offline_freeze();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8131e610)
Location: mm/util.c:1188
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff8131e610-ffffffff8131e62d: page_offline_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void page_offline_freeze();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813920f0)
Location: mm/util.c:1083
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff813920f0-ffffffff8139210d: page_offline_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void page_offline_freeze();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813c4af0)
Location: mm/util.c:1108
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
```
**Symbols:**

```
ffffffff813c4af0-ffffffff813c4b0d: page_offline_freeze (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void page_offline_freeze();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff813ef510)
Location: mm/util.c:1114
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
  - fs/proc/kcore.c:read_kcore_iter
```
**Symbols:**

```
ffffffff813ef510-ffffffff813ef52d: page_offline_freeze (STB_GLOBAL)
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
