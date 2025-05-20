# Function: <code>extcon_get_extcon_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff816ee3d0)
Location: drivers/extcon/extcon.c:450
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_register_interest
```
**Symbols:**

```
ffffffff816ee3d0-ffffffff816ee44d: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81753500)
Location: drivers/extcon/extcon.c:397
Inline: False
```
**Symbols:**

```
ffffffff81753500-ffffffff8175357c: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8177f6f0)
Location: drivers/extcon/extcon.c:873
Inline: False
```
**Symbols:**

```
ffffffff8177f6f0-ffffffff8177f76c: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8179ec10)
Location: drivers/extcon/extcon.c:887
Inline: True
```
**Symbols:**

```
ffffffff8179ec10-ffffffff8179ec8c: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81815d70)
Location: drivers/extcon/extcon.c:874
Inline: True
```
**Symbols:**

```
ffffffff81815d70-ffffffff81815dec: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8185fc30)
Location: drivers/extcon/extcon.c:875
Inline: True
```
**Symbols:**

```
ffffffff8185fc30-ffffffff8185fcac: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8187f5d0)
Location: drivers/extcon/extcon.c:875
Inline: True
```
**Symbols:**

```
ffffffff8187f5d0-ffffffff8187f64c: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818c9bf0)
Location: drivers/extcon/extcon.c:867
Inline: True
```
**Symbols:**

```
ffffffff818c9bf0-ffffffff818c9c6f: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818fc040)
Location: drivers/extcon/extcon.c:867
Inline: True
```
**Symbols:**

```
ffffffff818fc040-ffffffff818fc0bf: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d2160)
Location: drivers/extcon/extcon.c:867
Inline: True
```
**Symbols:**

```
ffffffff819d2160-ffffffff819d21df: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d1d40)
Location: drivers/extcon/extcon.c:867
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_extcon_init
```
**Symbols:**

```
ffffffff819d1d40-ffffffff819d1dbf: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819b7020)
Location: drivers/extcon/extcon.c:867
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff819b7020-ffffffff819b709f: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81a65bd0)
Location: drivers/extcon/extcon.c:867
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff81a65bd0-ffffffff81a65c4f: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81bd7170)
Location: drivers/extcon/extcon.c:861
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff81bd7170-ffffffff81bd71f9: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81d83a20)
Location: drivers/extcon/extcon.c:871
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff81d83a20-ffffffff81d83aa9: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81df1e10)
Location: drivers/extcon/extcon.c:881
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff81df1e10-ffffffff81df1e99: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81ea8460)
Location: drivers/extcon/extcon.c:881
Inline: True
Direct callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff81ea8460-ffffffff81ea84e9: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffff800010b881b0)
Location: drivers/extcon/extcon.c:867
Inline: True
```
**Symbols:**

```
ffff800010b881b0-ffff800010b88240: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (c0c6d1a0)
Location: drivers/extcon/extcon.c:867
Inline: True
```
**Symbols:**

```
c0c6d1a0-c0c6d224: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (c000000000c68440)
Location: drivers/extcon/extcon.c:867
Inline: True
```
**Symbols:**

```
c000000000c68440-c000000000c686b0: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffe000731872)
Location: drivers/extcon/extcon.c:867
Inline: True
```
**Symbols:**

```
ffffffe000731872-ffffffe0007318f6: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8189d370)
Location: drivers/extcon/extcon.c:867
Inline: True
```
**Symbols:**

```
ffffffff8189d370-ffffffff8189d3ef: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818eca60)
Location: drivers/extcon/extcon.c:867
Inline: True
```
**Symbols:**

```
ffffffff818eca60-ffffffff818ecadf: extcon_get_extcon_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_get_extcon_dev(const char *extcon_name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8190dae0)
Location: drivers/extcon/extcon.c:867
Inline: True
```
**Symbols:**

```
ffffffff8190dae0-ffffffff8190db5f: extcon_get_extcon_dev (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
