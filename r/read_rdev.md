# Function: <code>read_rdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81691fb0)
Location: drivers/md/md.c:9129
Inline: False
```
**Symbols:**

```
ffffffff81691fb0-ffffffff816920e4: read_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f5f60)
Location: drivers/md/md.c:8754
Inline: False
```
**Symbols:**

```
ffffffff816f5f60-ffffffff816f610b: read_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81727780)
Location: drivers/md/md.c:8811
Inline: False
```
**Symbols:**

```
ffffffff81727780-ffffffff81727942: read_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81740040)
Location: drivers/md/md.c:9061
Inline: False
```
**Symbols:**

```
ffffffff81740040-ffffffff817401c7: read_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817b26f0)
Location: drivers/md/md.c:9135
Inline: False
```
**Symbols:**

```
ffffffff817b26f0-ffffffff817b28de: read_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:9222
Inline: False
```
**Symbols:**

```
ffffffff817f5c60-ffffffff817f5e15: read_rdev (STB_LOCAL)
ffffffff818000df-ffffffff81800133: read_rdev.cold.83 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:9278
Inline: False
```
**Symbols:**

```
ffffffff81821be0-ffffffff81821d95: read_rdev (STB_LOCAL)
ffffffff8182c2ba-ffffffff8182c30e: read_rdev.cold.82 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:9346
Inline: False
```
**Symbols:**

```
ffffffff81864750-ffffffff8186490c: read_rdev (STB_LOCAL)
ffffffff8186e7f3-ffffffff8186e847: read_rdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:9452
Inline: False
```
**Symbols:**

```
ffffffff81896490-ffffffff8189664c: read_rdev (STB_LOCAL)
ffffffff818a05e3-ffffffff818a0637: read_rdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:9654
Inline: False
Direct callers:
  - drivers/md/md.c:md_reload_sb
  - drivers/md/md.c:md_reload_sb
```
**Symbols:**

```
ffffffff81963e00-ffffffff81963fc6: read_rdev (STB_LOCAL)
ffffffff81970117-ffffffff8197012f: read_rdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:9683
Inline: False
Direct callers:
  - drivers/md/md.c:md_reload_sb
  - drivers/md/md.c:md_reload_sb
```
**Symbols:**

```
ffffffff8196a6f0-ffffffff8196a8b2: read_rdev (STB_LOCAL)
ffffffff81c2626c-ffffffff81c26284: read_rdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:9661
Inline: False
Direct callers:
  - drivers/md/md.c:md_reload_sb
  - drivers/md/md.c:md_reload_sb
```
**Symbols:**

```
ffffffff8194e500-ffffffff8194e6c2: read_rdev (STB_LOCAL)
ffffffff81c183d2-ffffffff81c183ea: read_rdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:9726
Inline: False
Direct callers:
  - drivers/md/md.c:md_reload_sb
  - drivers/md/md.c:md_reload_sb
```
**Symbols:**

```
ffffffff819f3900-ffffffff819f3ad9: read_rdev (STB_LOCAL)
ffffffff81d2794a-ffffffff81d27962: read_rdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:9731
Inline: False
Direct callers:
  - drivers/md/md.c:md_reload_sb
  - drivers/md/md.c:md_reload_sb
```
**Symbols:**

```
ffffffff81b5d590-ffffffff81b5d7e1: read_rdev (STB_LOCAL)
ffffffff81ef3915-ffffffff81ef392a: read_rdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cf74e0)
Location: drivers/md/md.c:9751
Inline: False
Direct callers:
  - drivers/md/md.c:md_reload_sb
  - drivers/md/md.c:md_reload_sb
```
**Symbols:**

```
ffffffff81cf74e0-ffffffff81cf77ce: read_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d5ede0)
Location: drivers/md/md.c:9767
Inline: False
Direct callers:
  - drivers/md/md.c:md_reload_sb
  - drivers/md/md.c:md_reload_sb
```
**Symbols:**

```
ffffffff81d5ede0-ffffffff81d5f0bc: read_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e16050)
Location: drivers/md/md.c:9959
Inline: False
Direct callers:
  - drivers/md/md.c:md_reload_sb
  - drivers/md/md.c:md_reload_sb
```
**Symbols:**

```
ffffffff81e16050-ffffffff81e16323: read_rdev (STB_LOCAL)
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
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010ae9a38)
Location: drivers/md/md.c:9452
Inline: False
```
**Symbols:**

```
ffff800010ae9a38-ffff800010ae9c10: read_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bccd24)
Location: drivers/md/md.c:9452
Inline: False
```
**Symbols:**

```
c0bccd24-c0bccf08: read_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bd7250)
Location: drivers/md/md.c:9452
Inline: False
```
**Symbols:**

```
c000000000bd7250-c000000000bd7550: read_rdev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006de160)
Location: drivers/md/md.c:9452
Inline: False
```
**Symbols:**

```
ffffffe0006de160-ffffffe0006de2d6: read_rdev (STB_LOCAL)
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
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:9452
Inline: False
```
**Symbols:**

```
ffffffff8183c310-ffffffff8183c4cc: read_rdev (STB_LOCAL)
ffffffff81846463-ffffffff818464b7: read_rdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:9452
Inline: False
```
**Symbols:**

```
ffffffff81803970-ffffffff81803b2c: read_rdev (STB_LOCAL)
ffffffff8180dac3-ffffffff8180db17: read_rdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:9452
Inline: False
```
**Symbols:**

```
ffffffff8188b940-ffffffff8188bafc: read_rdev (STB_LOCAL)
ffffffff81895a93-ffffffff81895ae7: read_rdev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int read_rdev(struct mddev *mddev, struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:9452
Inline: False
```
**Symbols:**

```
ffffffff818aabb0-ffffffff818aad6c: read_rdev (STB_LOCAL)
ffffffff818b2411-ffffffff818b2465: read_rdev.cold (STB_LOCAL)
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
