# Function: <code>fill_ac</code>

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
In kernel/acct.c (ffffffff8110b9a5)
Location: kernel/acct.c:412
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
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
In kernel/acct.c (ffffffff81113205)
Location: kernel/acct.c:412
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
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
In kernel/acct.c (ffffffff8111a915)
Location: kernel/acct.c:412
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
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
In kernel/acct.c (ffffffff8111c465)
Location: kernel/acct.c:414
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
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
In kernel/acct.c (ffffffff81127b85)
Location: kernel/acct.c:415
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
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
In kernel/acct.c (ffffffff81135995)
Location: kernel/acct.c:415
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
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
In kernel/acct.c (ffffffff81141125)
Location: kernel/acct.c:415
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
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
In kernel/acct.c (ffffffff8114c545)
Location: kernel/acct.c:415
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
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
In kernel/acct.c (ffffffff81158215)
Location: kernel/acct.c:415
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fill_ac(acct_t *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81169190)
Location: kernel/acct.c:415
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff81169190-ffffffff8116950c: fill_ac (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void fill_ac(acct_t *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/acct.c (0)
Location: kernel/acct.c:413
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff81165830-ffffffff81165bf5: fill_ac (STB_LOCAL)
ffffffff81be4468-ffffffff81be4480: fill_ac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void fill_ac(acct_t *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/acct.c (0)
Location: kernel/acct.c:413
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff81166560-ffffffff81166929: fill_ac (STB_LOCAL)
ffffffff81bd6389-ffffffff81bd63a1: fill_ac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fill_ac(acct_t *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/acct.c (0)
Location: kernel/acct.c:413
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff8118bd20-ffffffff8118c0e9: fill_ac (STB_LOCAL)
ffffffff81cb2bb1-ffffffff81cb2bc9: fill_ac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fill_ac(acct_t *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/acct.c (0)
Location: kernel/acct.c:432
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff811bb100-ffffffff811bb4bc: fill_ac (STB_LOCAL)
ffffffff81e639e3-ffffffff81e639fb: fill_ac.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fill_ac(acct_t *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff811fcef0)
Location: kernel/acct.c:434
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff811fcef0-ffffffff811fd2c1: fill_ac (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fill_ac(acct_t *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81212090)
Location: kernel/acct.c:434
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff81212090-ffffffff81212451: fill_ac (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fill_ac(acct_t *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81229730)
Location: kernel/acct.c:434
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff81229730-ffffffff81229ad2: fill_ac (STB_LOCAL)
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
In kernel/acct.c (ffff8000101c7ac8)
Location: kernel/acct.c:415
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fill_ac(acct_t *ac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (c040e55c)
Location: kernel/acct.c:415
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
c040e55c-c040e950: fill_ac (STB_LOCAL)
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
In kernel/acct.c (c00000000022fc24)
Location: kernel/acct.c:415
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
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
In kernel/acct.c (ffffffe000147938)
Location: kernel/acct.c:415
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
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
In kernel/acct.c (ffffffff81150835)
Location: kernel/acct.c:415
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
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
In kernel/acct.c (ffffffff81143ae5)
Location: kernel/acct.c:415
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
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
In kernel/acct.c (ffffffff8114e6e5)
Location: kernel/acct.c:415
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
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
In kernel/acct.c (ffffffff8115b4c5)
Location: kernel/acct.c:415
Inline: True
Inline callers:
  - kernel/acct.c:do_acct_process
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
<b>Arch</b>
<ul>
</ul>
