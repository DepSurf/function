# Function: <code>md_run</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81697e60)
Location: drivers/md/md.c:5116
Inline: False
```
**Symbols:**

```
ffffffff81697e60-ffffffff81698877: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff816f8970)
Location: drivers/md/md.c:5131
Inline: False
```
**Symbols:**

```
ffffffff816f8970-ffffffff816f93cd: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff8172a180)
Location: drivers/md/md.c:5165
Inline: False
```
**Symbols:**

```
ffffffff8172a180-ffffffff8172ac50: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817429e0)
Location: drivers/md/md.c:5374
Inline: False
```
**Symbols:**

```
ffffffff817429e0-ffffffff81743518: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff817b4b00)
Location: drivers/md/md.c:5419
Inline: False
```
**Symbols:**

```
ffffffff817b4b00-ffffffff817b565b: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5436
Inline: False
```
**Symbols:**

```
ffffffff81800e8f-ffffffff8180100e: md_run.cold.90 (STB_LOCAL)
ffffffff817fc820-ffffffff817fd352: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5427
Inline: False
```
**Symbols:**

```
ffffffff8182d092-ffffffff8182d202: md_run.cold.89 (STB_LOCAL)
ffffffff81828910-ffffffff8182941f: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5495
Inline: False
```
**Symbols:**

```
ffffffff8186f666-ffffffff8186f7cd: md_run.cold (STB_LOCAL)
ffffffff8186ada0-ffffffff8186b868: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5591
Inline: False
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff818a1429-ffffffff818a15d2: md_run.cold (STB_LOCAL)
ffffffff8189cb40-ffffffff8189d64c: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5786
Inline: False
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff8197129b-ffffffff819713e6: md_run.cold (STB_LOCAL)
ffffffff8196d070-ffffffff8196d96f: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5821
Inline: False
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff81c27398-ffffffff81c274cb: md_run.cold (STB_LOCAL)
ffffffff81973ef0-ffffffff819748fa: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5780
Inline: False
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff81c19549-ffffffff81c1967b: md_run.cold (STB_LOCAL)
ffffffff81957f10-ffffffff8195891c: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5789
Inline: False
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff81d28b75-ffffffff81d28cbb: md_run.cold (STB_LOCAL)
ffffffff819fd690-ffffffff819fe0ba: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5778
Inline: False
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff81ef4bbe-ffffffff81ef4d19: md_run.cold (STB_LOCAL)
ffffffff81b64d10-ffffffff81b6564b: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5764
Inline: False
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff820a7ee6-ffffffff820a7efb: md_run.cold (STB_LOCAL)
ffffffff81cffdb0-ffffffff81d007f6: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5752
Inline: False
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff8212926a-ffffffff8212927f: md_run.cold (STB_LOCAL)
ffffffff81d62f70-ffffffff81d639d4: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5892
Inline: False
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff8220ac53-ffffffff8220ac68: md_run.cold (STB_LOCAL)
ffffffff81e19eb0-ffffffff81e1a928: md_run (STB_GLOBAL)
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
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffff800010af13e0)
Location: drivers/md/md.c:5591
Inline: False
Direct callers:
  - drivers/md/md.c:do_md_run
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffff800010af13e0-ffff800010af1f20: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c0bd2868)
Location: drivers/md/md.c:5591
Inline: False
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
c0bd2868-c0bd349c: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (c000000000bdd800)
Location: drivers/md/md.c:5591
Inline: False
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
c000000000bdd800-c000000000bde6d4: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffe0006e5290)
Location: drivers/md/md.c:5591
Inline: False
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffe0006e5290-ffffffe0006e5cf8: md_run (STB_GLOBAL)
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
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5591
Inline: False
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff818472a9-ffffffff81847452: md_run.cold (STB_LOCAL)
ffffffff818429c0-ffffffff818434cc: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5591
Inline: False
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff8180e909-ffffffff8180eab2: md_run.cold (STB_LOCAL)
ffffffff8180a020-ffffffff8180ab2c: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5591
Inline: False
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff818968d9-ffffffff81896a82: md_run.cold (STB_LOCAL)
ffffffff81891ff0-ffffffff81892afc: md_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int md_run(struct mddev *mddev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:5591
Inline: False
Direct callers:
  - drivers/md/md.c:do_md_run
```
**Symbols:**

```
ffffffff818b28b9-ffffffff818b2a62: md_run.cold (STB_LOCAL)
ffffffff818adbd0-ffffffff818ae6d7: md_run (STB_GLOBAL)
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
