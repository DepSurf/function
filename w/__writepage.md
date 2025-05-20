# Function: <code>__writepage</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision ⚠️</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81198500)
Location: mm/page-writeback.c:2302
Inline: False
```
```
In fs/ext4/inode.c (ffffffff8129afd0)
Location: fs/ext4/inode.c:2438
Inline: False
```
**Symbols:**

```
ffffffff81198500-ffffffff8119852d: __writepage (STB_LOCAL)
ffffffff8129afd0-ffffffff8129affc: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision ⚠️</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811ad450)
Location: mm/page-writeback.c:2347
Inline: False
```
```
In fs/ext4/inode.c (ffffffff812c90e0)
Location: fs/ext4/inode.c:2596
Inline: False
```
**Symbols:**

```
ffffffff811ad450-ffffffff811ad47d: __writepage (STB_LOCAL)
ffffffff812c90e0-ffffffff812c910c: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision ⚠️</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811bd9b0)
Location: mm/page-writeback.c:2314
Inline: False
```
```
In fs/ext4/inode.c (ffffffff812ded20)
Location: fs/ext4/inode.c:2622
Inline: False
```
**Symbols:**

```
ffffffff811bd9b0-ffffffff811bd9dd: __writepage (STB_LOCAL)
ffffffff812ded20-ffffffff812ded4c: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811c5f60)
Location: mm/page-writeback.c:2314
Inline: False
```
```
In fs/ext4/inode.c (ffffffff81302d40)
Location: fs/ext4/inode.c:2703
Inline: False
```
**Symbols:**

```
ffffffff811c5f60-ffffffff811c5fa5: __writepage (STB_LOCAL)
ffffffff81302d40-ffffffff81302d84: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811dad70)
Location: mm/page-writeback.c:2297
Inline: False
```
```
In fs/ext4/inode.c (ffffffff81327730)
Location: fs/ext4/inode.c:2696
Inline: False
```
**Symbols:**

```
ffffffff811dad70-ffffffff811dadbb: __writepage (STB_LOCAL)
ffffffff81327730-ffffffff81327774: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff811fbe70)
Location: mm/page-writeback.c:2298
Inline: False
```
**Symbols:**

```
ffffffff811fbe70-ffffffff811fbebb: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8120e750)
Location: mm/page-writeback.c:2292
Inline: False
```
**Symbols:**

```
ffffffff8120e750-ffffffff8120e79b: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8121e260)
Location: mm/page-writeback.c:2297
Inline: False
```
**Symbols:**

```
ffffffff8121e260-ffffffff8121e2ab: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff8122bd00)
Location: mm/page-writeback.c:2299
Inline: False
```
**Symbols:**

```
ffffffff8122bd00-ffffffff8122bd4b: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81258950)
Location: mm/page-writeback.c:2309
Inline: False
```
**Symbols:**

```
ffffffff81258950-ffffffff812589ae: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81262f30)
Location: mm/page-writeback.c:2307
Inline: False
```
**Symbols:**

```
ffffffff81262f30-ffffffff81262f93: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81267960)
Location: mm/page-writeback.c:2307
Inline: False
```
**Symbols:**

```
ffffffff81267960-ffffffff812679c3: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812a43d0)
Location: mm/page-writeback.c:2316
Inline: False
```
**Symbols:**

```
ffffffff812a43d0-ffffffff812a443c: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812fc510)
Location: mm/page-writeback.c:2395
Inline: False
```
**Symbols:**

```
ffffffff812fc510-ffffffff812fc587: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff813667e0)
Location: mm/page-writeback.c:2533
Inline: False
```
**Symbols:**

```
ffffffff813667e0-ffffffff81366857: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffff8000102bbde0)
Location: mm/page-writeback.c:2299
Inline: False
```
**Symbols:**

```
ffff8000102bbde0-ffff8000102bbe90: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c04e6914)
Location: mm/page-writeback.c:2299
Inline: False
```
**Symbols:**

```
c04e6914-c04e6970: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (c000000000372e90)
Location: mm/page-writeback.c:2299
Inline: False
```
**Symbols:**

```
c000000000372e90-c000000000372f58: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffe0001dd960)
Location: mm/page-writeback.c:2299
Inline: False
```
**Symbols:**

```
ffffffe0001dd960-ffffffe0001dd9c8: __writepage (STB_LOCAL)
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
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81224350)
Location: mm/page-writeback.c:2299
Inline: False
```
**Symbols:**

```
ffffffff81224350-ffffffff8122439b: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81217500)
Location: mm/page-writeback.c:2299
Inline: False
```
**Symbols:**

```
ffffffff81217500-ffffffff8121754b: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff812220f0)
Location: mm/page-writeback.c:2299
Inline: False
```
**Symbols:**

```
ffffffff812220f0-ffffffff8122213b: __writepage (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __writepage(struct page *page, struct writeback_control *wbc, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page-writeback.c (ffffffff81231540)
Location: mm/page-writeback.c:2299
Inline: False
```
**Symbols:**

```
ffffffff81231540-ffffffff8123158b: __writepage (STB_LOCAL)
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
