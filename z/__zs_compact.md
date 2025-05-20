# Function: <code>__zs_compact</code>

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
In mm/zsmalloc.c (ffffffff8120611f)
Location: mm/zsmalloc.c:1745
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff8122bce6)
Location: mm/zsmalloc.c:2261
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff8123e236)
Location: mm/zsmalloc.c:2221
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff81249be6)
Location: mm/zsmalloc.c:2200
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff81269ec2)
Location: mm/zsmalloc.c:2214
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff8128e828)
Location: mm/zsmalloc.c:2217
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff812a29c8)
Location: mm/zsmalloc.c:2217
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2263
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2265
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __zs_compact(struct zs_pool *pool, struct size_class *class);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813064d0)
Location: mm/zsmalloc.c:2267
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_shrinker_scan
```
**Symbols:**

```
ffffffff813064d0-ffffffff81306691: __zs_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int __zs_compact(struct zs_pool *pool, struct size_class *class);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81312230)
Location: mm/zsmalloc.c:2216
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
```
**Symbols:**

```
ffffffff81312230-ffffffff813123fa: __zs_compact (STB_LOCAL)
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
In mm/zsmalloc.c (ffffffff81317f64)
Location: mm/zsmalloc.c:2213
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffff8136446a)
Location: mm/zsmalloc.c:2213
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long unsigned int __zs_compact(struct zs_pool *pool, struct size_class *class);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff813e23a0)
Location: mm/zsmalloc.c:2072
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
```
**Symbols:**

```
ffffffff813e23a0-ffffffff813e279e: __zs_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int __zs_compact(struct zs_pool *pool, struct size_class *class);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff81469990)
Location: mm/zsmalloc.c:2261
Inline: False
Direct callers:
  - mm/zsmalloc.c:zs_compact
```
**Symbols:**

```
ffffffff81469990-ffffffff81469cdd: __zs_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int __zs_compact(struct zs_pool *pool, struct size_class *class);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff8149eb70)
Location: mm/zsmalloc.c:2008
Inline: False
```
**Symbols:**

```
ffffffff8149eb70-ffffffff8149eeb3: __zs_compact (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int __zs_compact(struct zs_pool *pool, struct size_class *class);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/zsmalloc.c (ffffffff814ce330)
Location: mm/zsmalloc.c:1990
Inline: False
```
**Symbols:**

```
ffffffff814ce330-ffffffff814ce61a: __zs_compact (STB_LOCAL)
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
In mm/zsmalloc.c (ffff8000103747e8)
Location: mm/zsmalloc.c:2265
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2265
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (c000000000467b44)
Location: mm/zsmalloc.c:2265
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (ffffffe00024d71e)
Location: mm/zsmalloc.c:2265
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2265
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2265
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2265
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
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
In mm/zsmalloc.c (0)
Location: mm/zsmalloc.c:2265
Inline: True
Inline callers:
  - mm/zsmalloc.c:zs_compact
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>long unsigned int</code>
</li>
</ul>
</details>
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
