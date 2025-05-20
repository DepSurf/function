# Function: <code>check_free_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff8110b7b0)
Location: kernel/acct.c:98
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff8110b7b0-ffffffff8110b8e5: check_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81113010)
Location: kernel/acct.c:98
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff81113010-ffffffff81113145: check_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff8111a720)
Location: kernel/acct.c:98
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff8111a720-ffffffff8111a855: check_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff8111c270)
Location: kernel/acct.c:100
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff8111c270-ffffffff8111c3a9: check_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81127990)
Location: kernel/acct.c:101
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff81127990-ffffffff81127ac9: check_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/acct.c (0)
Location: kernel/acct.c:101
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff811357e0-ffffffff811358dc: check_free_space (STB_LOCAL)
ffffffff81136599-ffffffff811365db: check_free_space.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/acct.c (0)
Location: kernel/acct.c:101
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff81140f70-ffffffff8114106c: check_free_space (STB_LOCAL)
ffffffff81141d29-ffffffff81141d6b: check_free_space.cold.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/acct.c (0)
Location: kernel/acct.c:101
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff8114c390-ffffffff8114c490: check_free_space (STB_LOCAL)
ffffffff8114d0d3-ffffffff8114d117: check_free_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/acct.c (0)
Location: kernel/acct.c:101
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff81158060-ffffffff81158160: check_free_space (STB_LOCAL)
ffffffff81158da8-ffffffff81158dec: check_free_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/acct.c (0)
Location: kernel/acct.c:101
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff81168c70-ffffffff81168d6d: check_free_space (STB_LOCAL)
ffffffff8116997b-ffffffff811699bf: check_free_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/acct.c (0)
Location: kernel/acct.c:101
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff81165300-ffffffff811653fd: check_free_space (STB_LOCAL)
ffffffff81be4424-ffffffff81be4468: check_free_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/acct.c (0)
Location: kernel/acct.c:101
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff811660d0-ffffffff811661cd: check_free_space (STB_LOCAL)
ffffffff81bd6345-ffffffff81bd6389: check_free_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/acct.c (0)
Location: kernel/acct.c:101
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff8118b890-ffffffff8118b98d: check_free_space (STB_LOCAL)
ffffffff81cb2b6d-ffffffff81cb2bb1: check_free_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/acct.c (0)
Location: kernel/acct.c:120
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff811bac20-ffffffff811bad3a: check_free_space (STB_LOCAL)
ffffffff81e639a3-ffffffff81e639e3: check_free_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff811fc9a0)
Location: kernel/acct.c:120
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff811fc9a0-ffffffff811fcae9: check_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81211b30)
Location: kernel/acct.c:120
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff81211b30-ffffffff81211c7c: check_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff812291b0)
Location: kernel/acct.c:120
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff812291b0-ffffffff812292fc: check_free_space (STB_LOCAL)
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
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffff8000101c7610)
Location: kernel/acct.c:101
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffff8000101c7610-ffff8000101c7758: check_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (c040e950)
Location: kernel/acct.c:101
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
c040e950-c040eb28: check_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (c00000000022f9b0)
Location: kernel/acct.c:101
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
c00000000022f9b0-c00000000022fb40: check_free_space (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffe0001477de)
Location: kernel/acct.c:101
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffe0001477de-ffffffe0001478c6: check_free_space (STB_LOCAL)
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
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/acct.c (0)
Location: kernel/acct.c:101
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff81150680-ffffffff81150780: check_free_space (STB_LOCAL)
ffffffff811513c8-ffffffff8115140c: check_free_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/acct.c (0)
Location: kernel/acct.c:101
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff81143930-ffffffff81143a30: check_free_space (STB_LOCAL)
ffffffff811446a8-ffffffff811446ec: check_free_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/acct.c (0)
Location: kernel/acct.c:101
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff8114e530-ffffffff8114e630: check_free_space (STB_LOCAL)
ffffffff8114f278-ffffffff8114f2bc: check_free_space.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int check_free_space(struct bsd_acct_struct *acct);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/acct.c (0)
Location: kernel/acct.c:101
Inline: False
Direct callers:
  - kernel/acct.c:do_acct_process
```
**Symbols:**

```
ffffffff8115b310-ffffffff8115b410: check_free_space (STB_LOCAL)
ffffffff8115c098-ffffffff8115c0dc: check_free_space.cold (STB_LOCAL)
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
