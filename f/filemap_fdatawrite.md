# Function: <code>filemap_fdatawrite</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118e950)
Location: mm/filemap.c:308
Inline: True
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffff8118e950-ffffffff8118e971: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a24e0)
Location: mm/filemap.c:387
Inline: True
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffff811a24e0-ffffffff811a2501: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b2320)
Location: mm/filemap.c:352
Inline: True
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffff811b2320-ffffffff811b2341: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b8fa0)
Location: mm/filemap.c:356
Inline: True
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffff811b8fa0-ffffffff811b8fc1: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cd8a0)
Location: mm/filemap.c:456
Inline: True
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffff811cd8a0-ffffffff811cd8c1: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ef3d0)
Location: mm/filemap.c:456
Inline: True
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffff811ef3d0-ffffffff811ef3f1: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81200bd0)
Location: mm/filemap.c:422
Inline: True
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffff81200bd0-ffffffff81200bf1: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812187f0)
Location: mm/filemap.c:426
Inline: True
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffff812187f0-ffffffff81218811: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81226070)
Location: mm/filemap.c:432
Inline: True
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffff81226070-ffffffff81226091: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812511b0)
Location: mm/filemap.c:432
Inline: False
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffff812511b0-ffffffff812511d1: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125c840)
Location: mm/filemap.c:433
Inline: False
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffff8125c840-ffffffff8125c861: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81261620)
Location: mm/filemap.c:424
Inline: False
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffff81261620-ffffffff81261641: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81299690)
Location: mm/filemap.c:442
Inline: False
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffff81299690-ffffffff812996f6: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812f5610)
Location: mm/filemap.c:430
Inline: False
Direct callers:
  - block/bdev.c:sync_bdevs
```
**Symbols:**

```
ffffffff812f5610-ffffffff812f563d: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135f470)
Location: mm/filemap.c:430
Inline: False
Direct callers:
  - block/bdev.c:sync_bdevs
```
**Symbols:**

```
ffffffff8135f470-ffffffff8135f49d: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813905d0)
Location: mm/filemap.c:435
Inline: False
Direct callers:
  - block/bdev.c:sync_bdevs
```
**Symbols:**

```
ffffffff813905d0-ffffffff813905fd: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813ba010)
Location: mm/filemap.c:430
Inline: False
Direct callers:
  - block/bdev.c:sync_bdevs
```
**Symbols:**

```
ffffffff813ba010-ffffffff813ba03d: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b32b0)
Location: mm/filemap.c:432
Inline: True
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffff8000102b32b0-ffff8000102b32e8: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e04c0)
Location: mm/filemap.c:432
Inline: True
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
c04e04c0-c04e0500: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000369e10)
Location: mm/filemap.c:432
Inline: True
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
c000000000369e10-c000000000369e34: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d89cc)
Location: mm/filemap.c:432
Inline: True
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffe0001d89cc-ffffffe0001d89fe: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121e6c0)
Location: mm/filemap.c:432
Inline: True
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffff8121e6c0-ffffffff8121e6e1: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81211880)
Location: mm/filemap.c:432
Inline: True
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffff81211880-ffffffff812118a1: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121c460)
Location: mm/filemap.c:432
Inline: True
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffff8121c460-ffffffff8121c481: filemap_fdatawrite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawrite(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122b4f0)
Location: mm/filemap.c:432
Inline: True
Direct callers:
  - fs/sync.c:fdatawrite_one_bdev
```
**Symbols:**

```
ffffffff8122b4f0-ffffffff8122b511: filemap_fdatawrite (STB_GLOBAL)
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
