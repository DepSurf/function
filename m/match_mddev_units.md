# Function: <code>match_mddev_units</code>

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
In drivers/md/md.c (ffffffff81692a5b)
Location: drivers/md/md.c:1942
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffff816f348a)
Location: drivers/md/md.c:1939
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffff81724b8a)
Location: drivers/md/md.c:1975
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffff8173ca44)
Location: drivers/md/md.c:2006
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffff817ae583)
Location: drivers/md/md.c:2053
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffff817f8c0e)
Location: drivers/md/md.c:2068
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffff81824c54)
Location: drivers/md/md.c:2061
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffff818670c8)
Location: drivers/md/md.c:2120
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffff81898e58)
Location: drivers/md/md.c:2174
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int match_mddev_units(struct mddev *mddev1, struct mddev *mddev2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8195e8c0)
Location: drivers/md/md.c:2300
Inline: False
Direct callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff8195e8c0-ffffffff8195e954: match_mddev_units (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int match_mddev_units(struct mddev *mddev1, struct mddev *mddev2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff819655e0)
Location: drivers/md/md.c:2316
Inline: False
Direct callers:
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff819655e0-ffffffff81965684: match_mddev_units (STB_LOCAL)
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
In drivers/md/md.c (ffffffff81953229)
Location: drivers/md/md.c:2275
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffff819f87f9)
Location: drivers/md/md.c:2277
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffff81b5fc7e)
Location: drivers/md/md.c:2272
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffff81cf989f)
Location: drivers/md/md.c:2263
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffff81d69098)
Location: drivers/md/md.c:2239
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffff81e1fec0)
Location: drivers/md/md.c:2369
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffff800010aecf4c)
Location: drivers/md/md.c:2174
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (c0bca68c)
Location: drivers/md/md.c:2174
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (c000000000bd2f1c)
Location: drivers/md/md.c:2174
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffe0006e1196)
Location: drivers/md/md.c:2174
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffff8183ecd8)
Location: drivers/md/md.c:2174
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffff81806338)
Location: drivers/md/md.c:2174
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffff8188e308)
Location: drivers/md/md.c:2174
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
In drivers/md/md.c (ffffffff818a775f)
Location: drivers/md/md.c:2174
Inline: True
Inline callers:
  - drivers/md/md.c:md_do_sync
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
