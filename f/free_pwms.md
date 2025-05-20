# Function: <code>free_pwms</code>

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
In drivers/pwm/core.c (ffffffff8142c5e5)
Location: drivers/pwm/core.c:72
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
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
In drivers/pwm/core.c (ffffffff814775af)
Location: drivers/pwm/core.c:72
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
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
In drivers/pwm/core.c (ffffffff81498914)
Location: drivers/pwm/core.c:72
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
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
In drivers/pwm/core.c (ffffffff814a2560)
Location: drivers/pwm/core.c:72
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
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
In drivers/pwm/core.c (ffffffff814e12b0)
Location: drivers/pwm/core.c:72
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
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
In drivers/pwm/core.c (ffffffff81510aa0)
Location: drivers/pwm/core.c:72
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
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
In drivers/pwm/core.c (ffffffff81526150)
Location: drivers/pwm/core.c:72
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
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
In drivers/pwm/core.c (ffffffff81555070)
Location: drivers/pwm/core.c:60
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
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
In drivers/pwm/core.c (ffffffff815766e0)
Location: drivers/pwm/core.c:60
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_pwms(struct pwm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8161b120)
Location: drivers/pwm/core.c:63
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwmchip_remove
```
**Symbols:**

```
ffffffff8161b120-ffffffff8161b18f: free_pwms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_pwms(struct pwm_chip *chip);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff816418a0)
Location: drivers/pwm/core.c:63
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwmchip_remove
```
**Symbols:**

```
ffffffff816418a0-ffffffff81641913: free_pwms (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81624867)
Location: drivers/pwm/core.c:53
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81693de5)
Location: drivers/pwm/core.c:53
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff817b47c5)
Location: drivers/pwm/core.c:53
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff818ceb55)
Location: drivers/pwm/core.c:60
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81911bd6)
Location: drivers/pwm/core.c:54
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/pwm/core.c (0)
Location: drivers/pwm/core.c:60
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
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
In drivers/pwm/core.c (0)
Location: drivers/pwm/core.c:60
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
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
In drivers/pwm/core.c (0)
Location: drivers/pwm/core.c:60
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
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
In drivers/pwm/core.c (ffffffe0004b1214)
Location: drivers/pwm/core.c:60
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
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
In drivers/pwm/core.c (ffffffff8156b4f0)
Location: drivers/pwm/core.c:60
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8156a430)
Location: drivers/pwm/core.c:60
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
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
In drivers/pwm/core.c (ffffffff81584930)
Location: drivers/pwm/core.c:60
Inline: True
Inline callers:
  - drivers/pwm/core.c:pwmchip_remove
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
</ul>
