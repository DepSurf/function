# Function: <code>tomoyo_warn_oom</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff81370ed0)
Location: security/tomoyo/memory.c:16
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff81370ed0-ffffffff81370f20: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff813a72b0)
Location: security/tomoyo/memory.c:16
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff813a72b0-ffffffff813a7300: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff813bde30)
Location: security/tomoyo/memory.c:16
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff813bde30-ffffffff813bde80: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff813d4700)
Location: security/tomoyo/memory.c:16
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff813d4700-ffffffff813d4750: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffff813fac10)
Location: security/tomoyo/memory.c:17
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff813fac10-ffffffff813fac60: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/memory.c (0)
Location: security/tomoyo/memory.c:17
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff8142bfc8-ffffffff8142bfee: tomoyo_warn_oom.cold.4 (STB_LOCAL)
ffffffff8142bbc0-ffffffff8142bbf5: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/memory.c (0)
Location: security/tomoyo/memory.c:17
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff81448915-ffffffff8144893b: tomoyo_warn_oom.cold.4 (STB_LOCAL)
ffffffff814484e0-ffffffff81448515: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/memory.c (0)
Location: security/tomoyo/memory.c:17
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff8147656c-ffffffff81476592: tomoyo_warn_oom.cold (STB_LOCAL)
ffffffff81476130-ffffffff81476165: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/memory.c (0)
Location: security/tomoyo/memory.c:17
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff8149030c-ffffffff81490332: tomoyo_warn_oom.cold (STB_LOCAL)
ffffffff8148fed0-ffffffff8148ff05: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/memory.c (ffffffff814e7283)
Location: security/tomoyo/memory.c:17
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff814e7669-ffffffff814e768f: tomoyo_warn_oom.cold (STB_LOCAL)
ffffffff814e7200-ffffffff814e7238: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/memory.c (ffffffff81504653)
Location: security/tomoyo/memory.c:17
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff81bf1431-ffffffff81bf1457: tomoyo_warn_oom.cold (STB_LOCAL)
ffffffff815045d0-ffffffff81504608: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/memory.c (ffffffff8150b1d3)
Location: security/tomoyo/memory.c:17
Inline: True
Inline callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
Direct callers:
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff81be35be-ffffffff81be35e4: tomoyo_warn_oom.cold (STB_LOCAL)
ffffffff8150b150-ffffffff8150b188: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/memory.c (0)
Location: security/tomoyo/memory.c:17
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_commit_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff81cd5ff7-ffffffff81cd6031: tomoyo_warn_oom.cold (STB_LOCAL)
ffffffff81568950-ffffffff81568994: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/memory.c (ffffffff81e88def)
Location: security/tomoyo/memory.c:17
Inline: True
Direct callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_commit_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff81e88dd5-ffffffff81e88e0f: tomoyo_warn_oom.cold (STB_LOCAL)
ffffffff81604640-ffffffff8160468e: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/memory.c (ffffffff816b593b)
Location: security/tomoyo/memory.c:17
Inline: True
Direct callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_commit_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff820748c8-ffffffff820748dc: tomoyo_warn_oom.cold (STB_LOCAL)
ffffffff816b58e0-ffffffff816b5947: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/memory.c (ffffffff816ee31b)
Location: security/tomoyo/memory.c:17
Inline: True
Direct callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_commit_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff820f441e-ffffffff820f4432: tomoyo_warn_oom.cold (STB_LOCAL)
ffffffff816ee2c0-ffffffff816ee327: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/tomoyo/memory.c (ffffffff8172b0eb)
Location: security/tomoyo/memory.c:17
Inline: True
Direct callers:
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/memory.c:tomoyo_commit_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff821d1863-ffffffff821d1877: tomoyo_warn_oom.cold (STB_LOCAL)
ffffffff8172b090-ffffffff8172b0f7: tomoyo_warn_oom (STB_GLOBAL)
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
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffff800010583ff0)
Location: security/tomoyo/memory.c:17
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffff800010583ff0-ffff800010584064: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (c0735aec)
Location: security/tomoyo/memory.c:17
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
c0735aec-c0735b60: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (c0000000006f2f10)
Location: security/tomoyo/memory.c:17
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
c0000000006f2f10-c0000000006f2fa8: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/memory.c (ffffffe0003d40e2)
Location: security/tomoyo/memory.c:17
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffe0003d40e2-ffffffe0003d4150: tomoyo_warn_oom (STB_GLOBAL)
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
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/memory.c (0)
Location: security/tomoyo/memory.c:17
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff814888ec-ffffffff81488912: tomoyo_warn_oom.cold (STB_LOCAL)
ffffffff814884b0-ffffffff814884e5: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/memory.c (0)
Location: security/tomoyo/memory.c:17
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff8147930c-ffffffff81479332: tomoyo_warn_oom.cold (STB_LOCAL)
ffffffff81478ed0-ffffffff81478f05: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/memory.c (0)
Location: security/tomoyo/memory.c:17
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff8148498c-ffffffff814849b2: tomoyo_warn_oom.cold (STB_LOCAL)
ffffffff81484550-ffffffff81484585: tomoyo_warn_oom (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void tomoyo_warn_oom(const char *function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/memory.c (0)
Location: security/tomoyo/memory.c:17
Inline: False
Direct callers:
  - security/tomoyo/memory.c:tomoyo_memory_ok
  - security/tomoyo/realpath.c:tomoyo_realpath_from_path
```
**Symbols:**

```
ffffffff8149c4cc-ffffffff8149c4f2: tomoyo_warn_oom.cold (STB_LOCAL)
ffffffff8149c090-ffffffff8149c0c5: tomoyo_warn_oom (STB_GLOBAL)
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
