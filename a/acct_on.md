# Function: <code>acct_on</code>

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
In kernel/acct.c (ffffffff8110beaa)
Location: kernel/acct.c:190
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
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
In kernel/acct.c (ffffffff8111370a)
Location: kernel/acct.c:190
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
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
In kernel/acct.c (ffffffff8111ae1a)
Location: kernel/acct.c:190
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
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
In kernel/acct.c (ffffffff8111ca3a)
Location: kernel/acct.c:192
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
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
In kernel/acct.c (ffffffff8112815a)
Location: kernel/acct.c:193
Inline: True
Inline callers:
  - kernel/acct.c:SyS_acct
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int acct_on(struct filename *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81135f50)
Location: kernel/acct.c:193
Inline: False
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
```
**Symbols:**

```
ffffffff81135f50-ffffffff811361ac: acct_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int acct_on(struct filename *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff811416e0)
Location: kernel/acct.c:193
Inline: False
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
```
**Symbols:**

```
ffffffff811416e0-ffffffff8114193c: acct_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int acct_on(struct filename *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff8114ca30)
Location: kernel/acct.c:193
Inline: False
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
```
**Symbols:**

```
ffffffff8114ca30-ffffffff8114cca0: acct_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int acct_on(struct filename *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81158700)
Location: kernel/acct.c:193
Inline: False
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
```
**Symbols:**

```
ffffffff81158700-ffffffff81158970: acct_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acct_on(struct filename *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81168d70)
Location: kernel/acct.c:193
Inline: False
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
```
**Symbols:**

```
ffffffff81168d70-ffffffff81168fdd: acct_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acct_on(struct filename *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81165400)
Location: kernel/acct.c:193
Inline: False
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
```
**Symbols:**

```
ffffffff81165400-ffffffff8116566d: acct_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acct_on(struct filename *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff811661d0)
Location: kernel/acct.c:193
Inline: False
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
```
**Symbols:**

```
ffffffff811661d0-ffffffff8116643d: acct_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acct_on(struct filename *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff8118b990)
Location: kernel/acct.c:193
Inline: False
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
```
**Symbols:**

```
ffffffff8118b990-ffffffff8118bbfd: acct_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acct_on(struct filename *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff811bad40)
Location: kernel/acct.c:212
Inline: False
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
```
**Symbols:**

```
ffffffff811bad40-ffffffff811bafb6: acct_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acct_on(struct filename *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff811fcb00)
Location: kernel/acct.c:212
Inline: False
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
```
**Symbols:**

```
ffffffff811fcb00-ffffffff811fcd76: acct_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acct_on(struct filename *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81211c90)
Location: kernel/acct.c:212
Inline: False
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
```
**Symbols:**

```
ffffffff81211c90-ffffffff81211f12: acct_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acct_on(struct filename *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81229310)
Location: kernel/acct.c:212
Inline: False
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
```
**Symbols:**

```
ffffffff81229310-ffffffff812295be: acct_on (STB_LOCAL)
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
In kernel/acct.c (ffff8000101c77b4)
Location: kernel/acct.c:193
Inline: True
Inline callers:
  - kernel/acct.c:__arm64_sys_acct
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
In kernel/acct.c (c040edbc)
Location: kernel/acct.c:193
Inline: True
Inline callers:
  - kernel/acct.c:__se_sys_acct
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
In kernel/acct.c (c000000000230354)
Location: kernel/acct.c:193
Inline: True
Inline callers:
  - kernel/acct.c:__se_sys_acct
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
In kernel/acct.c (ffffffe000147dae)
Location: kernel/acct.c:193
Inline: True
Inline callers:
  - kernel/acct.c:__se_sys_acct
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
int acct_on(struct filename *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81150d20)
Location: kernel/acct.c:193
Inline: False
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
```
**Symbols:**

```
ffffffff81150d20-ffffffff81150f90: acct_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int acct_on(struct filename *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff81143fd0)
Location: kernel/acct.c:193
Inline: False
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
```
**Symbols:**

```
ffffffff81143fd0-ffffffff81144240: acct_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int acct_on(struct filename *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff8114ebd0)
Location: kernel/acct.c:193
Inline: False
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
```
**Symbols:**

```
ffffffff8114ebd0-ffffffff8114ee40: acct_on (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int acct_on(struct filename *pathname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/acct.c (ffffffff8115b9b0)
Location: kernel/acct.c:193
Inline: False
Direct callers:
  - kernel/acct.c:__ia32_sys_acct
  - kernel/acct.c:__x64_sys_acct
```
**Symbols:**

```
ffffffff8115b9b0-ffffffff8115bc25: acct_on (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
