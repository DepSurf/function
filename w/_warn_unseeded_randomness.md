# Function: <code>_warn_unseeded_randomness</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff815a5c10)
Location: drivers/char/random.c:1478
Inline: True
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
```
**Symbols:**

```
ffffffff815a5c10-ffffffff815a5c57: _warn_unseeded_randomness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffff8160c510)
Location: drivers/char/random.c:1477
Inline: True
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
```
**Symbols:**

```
ffffffff8160c510-ffffffff8160c557: _warn_unseeded_randomness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (0)
Location: drivers/char/random.c:1581
Inline: True
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes_arch
```
**Symbols:**

```
ffffffff81645e00-ffffffff81645e57: _warn_unseeded_randomness (STB_LOCAL)
ffffffff81649170-ffffffff8164918d: _warn_unseeded_randomness.cold.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff81667470)
Location: drivers/char/random.c:1590
Inline: True
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffff81664100-ffffffff81664157: _warn_unseeded_randomness (STB_LOCAL)
ffffffff81667470-ffffffff8166748d: _warn_unseeded_randomness.cold.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff8169cf00)
Location: drivers/char/random.c:1672
Inline: True
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffff81699a00-ffffffff81699a5e: _warn_unseeded_randomness (STB_LOCAL)
ffffffff8169cf00-ffffffff8169cf1d: _warn_unseeded_randomness.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff816bfc70)
Location: drivers/char/random.c:1672
Inline: True
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffff816bc610-ffffffff816bc66e: _warn_unseeded_randomness (STB_LOCAL)
ffffffff816bfc70-ffffffff816bfc8d: _warn_unseeded_randomness.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff81773648)
Location: drivers/char/random.c:1517
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:get_random_bytes
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
```
**Symbols:**

```
ffffffff81770990-ffffffff817709e9: _warn_unseeded_randomness (STB_LOCAL)
ffffffff81773b50-ffffffff81773b6d: _warn_unseeded_randomness.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff8178e608)
Location: drivers/char/random.c:1516
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:get_random_bytes
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
```
**Symbols:**

```
ffffffff8178ba00-ffffffff8178ba59: _warn_unseeded_randomness (STB_LOCAL)
ffffffff81c084e5-ffffffff81c08502: _warn_unseeded_randomness.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff81770e68)
Location: drivers/char/random.c:1492
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:get_random_bytes
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
```
**Symbols:**

```
ffffffff8176ec10-ffffffff8176ec69: _warn_unseeded_randomness (STB_LOCAL)
ffffffff81bfa0aa-ffffffff81bfa0c7: _warn_unseeded_randomness.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff817f6991)
Location: drivers/char/random.c:1512
Inline: True
Inline callers:
  - drivers/char/random.c:get_random_bytes
  - drivers/char/random.c:get_random_bytes
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
```
**Symbols:**

```
ffffffff817f4480-ffffffff817f44f0: _warn_unseeded_randomness (STB_LOCAL)
ffffffff81cfa984-ffffffff81cfa9bd: _warn_unseeded_randomness.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffff8000108ac550)
Location: drivers/char/random.c:1672
Inline: True
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffff8000108ac550-ffff8000108ac5f4: _warn_unseeded_randomness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c09a96e8)
Location: drivers/char/random.c:1672
Inline: True
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
c09a96e8-c09a977c: _warn_unseeded_randomness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (c000000000945e90)
Location: drivers/char/random.c:1672
Inline: True
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
c000000000945e90-c000000000945f64: _warn_unseeded_randomness (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/random.c (ffffffe000561708)
Location: drivers/char/random.c:1672
Inline: True
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffe000561708-ffffffe00056179c: _warn_unseeded_randomness (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff816856c0)
Location: drivers/char/random.c:1672
Inline: True
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffff81682070-ffffffff816820ce: _warn_unseeded_randomness (STB_LOCAL)
ffffffff816856c0-ffffffff816856dd: _warn_unseeded_randomness.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff81663360)
Location: drivers/char/random.c:1672
Inline: True
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffff8165fef0-ffffffff8165ff4e: _warn_unseeded_randomness (STB_LOCAL)
ffffffff81663360-ffffffff8166337d: _warn_unseeded_randomness.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff816b3ab0)
Location: drivers/char/random.c:1672
Inline: True
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffff816b0450-ffffffff816b04ae: _warn_unseeded_randomness (STB_LOCAL)
ffffffff816b3ab0-ffffffff816b3acd: _warn_unseeded_randomness.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void _warn_unseeded_randomness(const char *func_name, void *caller, void **previous);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/random.c (ffffffff816ce010)
Location: drivers/char/random.c:1672
Inline: True
Direct callers:
  - drivers/char/random.c:get_random_u32
  - drivers/char/random.c:get_random_u64
  - drivers/char/random.c:get_random_bytes
```
**Symbols:**

```
ffffffff816caba0-ffffffff816cabfe: _warn_unseeded_randomness (STB_LOCAL)
ffffffff816ce010-ffffffff816ce02d: _warn_unseeded_randomness.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
