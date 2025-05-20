# Function: <code>reset_control_rearm</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int reset_control_rearm(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8174e890)
Location: drivers/reset/core.c:376
Inline: True
```
**Symbols:**

```
ffffffff8174e890-ffffffff8174e8f3: reset_control_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int reset_control_rearm(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732400)
Location: drivers/reset/core.c:400
Inline: True
```
**Symbols:**

```
ffffffff81732400-ffffffff817324e8: reset_control_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reset_control_rearm(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (ffffffff817b2c34)
Location: drivers/reset/core.c:400
Inline: True
```
**Symbols:**

```
ffffffff81cf853e-ffffffff81cf85c2: reset_control_rearm.cold (STB_LOCAL)
ffffffff817b2bf0-ffffffff817b2d9a: reset_control_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int reset_control_rearm(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:401
Inline: False
```
**Symbols:**

```
ffffffff81ec063b-ffffffff81ec06bf: reset_control_rearm.cold (STB_LOCAL)
ffffffff818ee610-ffffffff818ee7a3: reset_control_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int reset_control_rearm(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:401
Inline: False
```
**Symbols:**

```
ffffffff82094da1-ffffffff82094e25: reset_control_rearm.cold (STB_LOCAL)
ffffffff81a46240-ffffffff81a463d3: reset_control_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int reset_control_rearm(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:401
Inline: False
```
**Symbols:**

```
ffffffff82115bc6-ffffffff82115c4a: reset_control_rearm.cold (STB_LOCAL)
ffffffff81a903f0-ffffffff81a9058d: reset_control_rearm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int reset_control_rearm(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:401
Inline: False
```
**Symbols:**

```
ffffffff821f38cc-ffffffff821f3950: reset_control_rearm.cold (STB_LOCAL)
ffffffff81ae2e30-ffffffff81ae2fcd: reset_control_rearm (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
