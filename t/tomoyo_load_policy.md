# Function: <code>tomoyo_load_policy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/load_policy.c (ffffffff81370d90)
Location: security/tomoyo/load_policy.c:83
Inline: False
```
**Symbols:**

```
ffffffff81370d90-ffffffff81370ec7: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/load_policy.c (ffffffff813a7180)
Location: security/tomoyo/load_policy.c:83
Inline: False
```
**Symbols:**

```
ffffffff813a7180-ffffffff813a72af: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/load_policy.c (ffffffff813bdd00)
Location: security/tomoyo/load_policy.c:83
Inline: False
```
**Symbols:**

```
ffffffff813bdd00-ffffffff813bde2f: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/load_policy.c (ffffffff813d45d0)
Location: security/tomoyo/load_policy.c:83
Inline: False
```
**Symbols:**

```
ffffffff813d45d0-ffffffff813d46ff: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/load_policy.c (ffffffff813faae0)
Location: security/tomoyo/load_policy.c:84
Inline: False
```
**Symbols:**

```
ffffffff813faae0-ffffffff813fac0f: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/load_policy.c (0)
Location: security/tomoyo/load_policy.c:84
Inline: False
```
**Symbols:**

```
ffffffff8142bb9a-ffffffff8142bbb2: tomoyo_load_policy.cold.0 (STB_LOCAL)
ffffffff8142ba80-ffffffff8142bb9a: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/load_policy.c (0)
Location: security/tomoyo/load_policy.c:84
Inline: False
```
**Symbols:**

```
ffffffff814484ba-ffffffff814484d2: tomoyo_load_policy.cold.0 (STB_LOCAL)
ffffffff814483a0-ffffffff814484ba: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/load_policy.c (0)
Location: security/tomoyo/load_policy.c:85
Inline: False
```
**Symbols:**

```
ffffffff814760ff-ffffffff81476117: tomoyo_load_policy.cold (STB_LOCAL)
ffffffff81475fe0-ffffffff814760ff: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/load_policy.c (0)
Location: security/tomoyo/load_policy.c:85
Inline: False
```
**Symbols:**

```
ffffffff8148fe9f-ffffffff8148feb7: tomoyo_load_policy.cold (STB_LOCAL)
ffffffff8148fd80-ffffffff8148fe9f: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/load_policy.c (0)
Location: security/tomoyo/load_policy.c:85
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff814e71bf-ffffffff814e71d7: tomoyo_load_policy.cold (STB_LOCAL)
ffffffff814e70a0-ffffffff814e71bf: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/load_policy.c (0)
Location: security/tomoyo/load_policy.c:85
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff81bf1419-ffffffff81bf1431: tomoyo_load_policy.cold (STB_LOCAL)
ffffffff815044b0-ffffffff815045cf: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/load_policy.c (0)
Location: security/tomoyo/load_policy.c:85
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff81be35a6-ffffffff81be35be: tomoyo_load_policy.cold (STB_LOCAL)
ffffffff8150b030-ffffffff8150b14f: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/load_policy.c (0)
Location: security/tomoyo/load_policy.c:85
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff81cd5fb7-ffffffff81cd5ff7: tomoyo_load_policy.cold (STB_LOCAL)
ffffffff81568800-ffffffff81568947: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/load_policy.c (0)
Location: security/tomoyo/load_policy.c:85
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff81e88d93-ffffffff81e88dd5: tomoyo_load_policy.cold (STB_LOCAL)
ffffffff816044b0-ffffffff8160463f: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/load_policy.c (0)
Location: security/tomoyo/load_policy.c:85
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff8207489e-ffffffff820748c8: tomoyo_load_policy.cold (STB_LOCAL)
ffffffff816b5720-ffffffff816b58cb: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/load_policy.c (0)
Location: security/tomoyo/load_policy.c:85
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff820f43f4-ffffffff820f441e: tomoyo_load_policy.cold (STB_LOCAL)
ffffffff816ee100-ffffffff816ee2ab: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/load_policy.c (0)
Location: security/tomoyo/load_policy.c:85
Inline: False
Direct callers:
  - security/tomoyo/tomoyo.c:tomoyo_bprm_creds_for_exec
```
**Symbols:**

```
ffffffff821d1839-ffffffff821d1863: tomoyo_load_policy.cold (STB_LOCAL)
ffffffff8172aed0-ffffffff8172b07b: tomoyo_load_policy (STB_GLOBAL)
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
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/load_policy.c (ffff800010583e90)
Location: security/tomoyo/load_policy.c:85
Inline: False
```
**Symbols:**

```
ffff800010583e90-ffff800010583fcc: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/load_policy.c (c07359b8)
Location: security/tomoyo/load_policy.c:85
Inline: False
```
**Symbols:**

```
c07359b8-c0735aec: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/load_policy.c (c0000000006f2bc0)
Location: security/tomoyo/load_policy.c:85
Inline: False
```
**Symbols:**

```
c0000000006f2bc0-c0000000006f2ed8: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/load_policy.c (ffffffe0003d3f7a)
Location: security/tomoyo/load_policy.c:85
Inline: False
```
**Symbols:**

```
ffffffe0003d3f7a-ffffffe0003d407c: tomoyo_load_policy (STB_GLOBAL)
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
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/load_policy.c (0)
Location: security/tomoyo/load_policy.c:85
Inline: False
```
**Symbols:**

```
ffffffff8148847f-ffffffff81488497: tomoyo_load_policy.cold (STB_LOCAL)
ffffffff81488360-ffffffff8148847f: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/load_policy.c (0)
Location: security/tomoyo/load_policy.c:85
Inline: False
```
**Symbols:**

```
ffffffff81478e9f-ffffffff81478eb7: tomoyo_load_policy.cold (STB_LOCAL)
ffffffff81478d80-ffffffff81478e9f: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/load_policy.c (0)
Location: security/tomoyo/load_policy.c:85
Inline: False
```
**Symbols:**

```
ffffffff8148451f-ffffffff81484537: tomoyo_load_policy.cold (STB_LOCAL)
ffffffff81484400-ffffffff8148451f: tomoyo_load_policy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void tomoyo_load_policy(const char *filename);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/load_policy.c (0)
Location: security/tomoyo/load_policy.c:85
Inline: False
```
**Symbols:**

```
ffffffff8149c05f-ffffffff8149c077: tomoyo_load_policy.cold (STB_LOCAL)
ffffffff8149bf40-ffffffff8149c05f: tomoyo_load_policy (STB_GLOBAL)
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
