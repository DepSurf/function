# Function: <code>__dm_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a1e80)
Location: drivers/md/dm.c:2871
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy
  - drivers/md/dm.c:dm_destroy_immediate
```
**Symbols:**

```
ffffffff816a1e80-ffffffff816a20c2: __dm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81702b10)
Location: drivers/md/dm.c:1874
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff81702b10-ffffffff81702d29: __dm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817349d0)
Location: drivers/md/dm.c:1931
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff817349d0-ffffffff81734bf8: __dm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174dd90)
Location: drivers/md/dm.c:2141
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff8174dd90-ffffffff8174dfb8: __dm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817bfe20)
Location: drivers/md/dm.c:2115
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff817bfe20-ffffffff817c0025: __dm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2305
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff81809160-ffffffff818092b8: __dm_destroy (STB_LOCAL)
ffffffff8180aa29-ffffffff8180aa47: __dm_destroy.cold.56 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2334
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff818352b0-ffffffff818353e6: __dm_destroy (STB_LOCAL)
ffffffff81836a29-ffffffff81836a47: __dm_destroy.cold.60 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2365
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff81877c70-ffffffff81877dcd: __dm_destroy (STB_LOCAL)
ffffffff81879627-ffffffff81879648: __dm_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2369
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff818a9a90-ffffffff818a9bf4: __dm_destroy (STB_LOCAL)
ffffffff818ab428-ffffffff818ab449: __dm_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2372
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff81979cf0-ffffffff81979e5b: __dm_destroy (STB_LOCAL)
ffffffff8197b5f9-ffffffff8197b61a: __dm_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2238
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff8197e600-ffffffff8197e76b: __dm_destroy (STB_LOCAL)
ffffffff81c280d2-ffffffff81c280f3: __dm_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2257
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff81962450-ffffffff819625bb: __dm_destroy (STB_LOCAL)
ffffffff81c1a289-ffffffff81c1a2aa: __dm_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2147
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff81a09600-ffffffff81a097f6: __dm_destroy (STB_LOCAL)
ffffffff81d29eeb-ffffffff81d29f44: __dm_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2329
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff81b71690-ffffffff81b7186b: __dm_destroy (STB_LOCAL)
ffffffff81ef61ef-ffffffff81ef623e: __dm_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0e4e0)
Location: drivers/md/dm.c:2431
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff81d0e4e0-ffffffff81d0e6cc: __dm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d77ae0)
Location: drivers/md/dm.c:2467
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff81d77ae0-ffffffff81d77cd6: __dm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2ed10)
Location: drivers/md/dm.c:2475
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff81e2ed10-ffffffff81e2ef06: __dm_destroy (STB_LOCAL)
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
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afe050)
Location: drivers/md/dm.c:2369
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffff800010afe050-ffff800010afe230: __dm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdf740)
Location: drivers/md/dm.c:2369
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
c0bdf740-c0bdf8ec: __dm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000beeec0)
Location: drivers/md/dm.c:2369
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
c000000000beeec0-c000000000bef120: __dm_destroy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006efee4)
Location: drivers/md/dm.c:2369
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffe0006efee4-ffffffe0006f0098: __dm_destroy (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2369
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff8184f910-ffffffff8184fa74: __dm_destroy (STB_LOCAL)
ffffffff818512a8-ffffffff818512c9: __dm_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2369
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff81816f20-ffffffff81817084: __dm_destroy (STB_LOCAL)
ffffffff818188b8-ffffffff818188d9: __dm_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2369
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff8189ef40-ffffffff8189f0a4: __dm_destroy (STB_LOCAL)
ffffffff818a08d8-ffffffff818a08f9: __dm_destroy.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void __dm_destroy(struct mapped_device *md, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (0)
Location: drivers/md/dm.c:2369
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_destroy_immediate
  - drivers/md/dm.c:dm_destroy
```
**Symbols:**

```
ffffffff818bb630-ffffffff818bb78d: __dm_destroy (STB_LOCAL)
ffffffff818bcb29-ffffffff818bcb4a: __dm_destroy.cold (STB_LOCAL)
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
