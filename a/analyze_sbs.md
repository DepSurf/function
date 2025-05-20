# Function: <code>analyze_sbs</code>

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
In drivers/md/md.c (ffffffff81697ed9)
Location: drivers/md/md.c:3268
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff816f89f3)
Location: drivers/md/md.c:3274
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff8172a203)
Location: drivers/md/md.c:3313
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff81742a59)
Location: drivers/md/md.c:3449
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff817b4b79)
Location: drivers/md/md.c:3504
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff817fc895)
Location: drivers/md/md.c:3520
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff8182898e)
Location: drivers/md/md.c:3511
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff8186ae1c)
Location: drivers/md/md.c:3578
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff8189cbba)
Location: drivers/md/md.c:3632
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int analyze_sbs(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3757
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff8196cde0-ffffffff8196d063: analyze_sbs (STB_LOCAL)
ffffffff81971257-ffffffff8197129b: analyze_sbs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int analyze_sbs(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3778
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81973c60-ffffffff81973ee3: analyze_sbs (STB_LOCAL)
ffffffff81c27354-ffffffff81c27398: analyze_sbs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int analyze_sbs(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3742
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81957c90-ffffffff81957f0c: analyze_sbs (STB_LOCAL)
ffffffff81c19505-ffffffff81c19549: analyze_sbs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int analyze_sbs(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3761
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff819fd3b0-ffffffff819fd688: analyze_sbs (STB_LOCAL)
ffffffff81d28b2e-ffffffff81d28b75: analyze_sbs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int analyze_sbs(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (0)
Location: drivers/md/md.c:3752
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81b64ac0-ffffffff81b64d03: analyze_sbs (STB_LOCAL)
ffffffff81ef4b0d-ffffffff81ef4bbe: analyze_sbs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int analyze_sbs(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cffac0)
Location: drivers/md/md.c:3714
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81cffac0-ffffffff81cffd98: analyze_sbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int analyze_sbs(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d61f20)
Location: drivers/md/md.c:3699
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81d61f20-ffffffff81d621fe: analyze_sbs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int analyze_sbs(struct mddev *mddev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e18eb0)
Location: drivers/md/md.c:3832
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
```
**Symbols:**

```
ffffffff81e18eb0-ffffffff81e19144: analyze_sbs (STB_LOCAL)
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
In drivers/md/md.c (ffff800010af1448)
Location: drivers/md/md.c:3632
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (c0bd28e0)
Location: drivers/md/md.c:3632
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (c000000000bdd894)
Location: drivers/md/md.c:3632
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffe0006e52ea)
Location: drivers/md/md.c:3632
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff81842a3a)
Location: drivers/md/md.c:3632
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff8180a09a)
Location: drivers/md/md.c:3632
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff8189206a)
Location: drivers/md/md.c:3632
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
In drivers/md/md.c (ffffffff818adc4a)
Location: drivers/md/md.c:3632
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
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
