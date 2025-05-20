# Function: <code>rc5t583_irq_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (ffffffff815958b0)
Location: drivers/mfd/rc5t583-irq.c:335
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff815958b0-ffffffff81595b19: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (ffffffff815ea6f0)
Location: drivers/mfd/rc5t583-irq.c:335
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff815ea6f0-ffffffff815ea954: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (ffffffff81617500)
Location: drivers/mfd/rc5t583-irq.c:335
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff81617500-ffffffff81617764: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (ffffffff8162b3e0)
Location: drivers/mfd/rc5t583-irq.c:335
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff8162b3e0-ffffffff8162b678: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (ffffffff81693d20)
Location: drivers/mfd/rc5t583-irq.c:335
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff81693d20-ffffffff81693fb8: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (ffffffff816cfe70)
Location: drivers/mfd/rc5t583-irq.c:335
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff816cfe70-ffffffff816d0106: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (ffffffff816f1490)
Location: drivers/mfd/rc5t583-irq.c:335
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff816f1490-ffffffff816f1726: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (0)
Location: drivers/mfd/rc5t583-irq.c:323
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff8172accc-ffffffff8172ad73: rc5t583_irq_init.cold (STB_LOCAL)
ffffffff8172aa80-ffffffff8172ac1b: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (0)
Location: drivers/mfd/rc5t583-irq.c:323
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff8174eecc-ffffffff8174ef73: rc5t583_irq_init.cold (STB_LOCAL)
ffffffff8174ec80-ffffffff8174ee1b: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (0)
Location: drivers/mfd/rc5t583-irq.c:323
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff8180d5be-ffffffff8180d67b: rc5t583_irq_init.cold (STB_LOCAL)
ffffffff8180d320-ffffffff8180d4dd: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (0)
Location: drivers/mfd/rc5t583-irq.c:323
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff81c15704-ffffffff81c157c1: rc5t583_irq_init.cold (STB_LOCAL)
ffffffff8181c2b0-ffffffff8181c46d: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (0)
Location: drivers/mfd/rc5t583-irq.c:323
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff81c0745b-ffffffff81c07518: rc5t583_irq_init.cold (STB_LOCAL)
ffffffff817ff670-ffffffff817ff82d: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (0)
Location: drivers/mfd/rc5t583-irq.c:323
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff81d0ab6f-ffffffff81d0abc1: rc5t583_irq_init.cold (STB_LOCAL)
ffffffff81889d50-ffffffff8188a00b: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (0)
Location: drivers/mfd/rc5t583-irq.c:323
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff81ed3034-ffffffff81ed3086: rc5t583_irq_init.cold (STB_LOCAL)
ffffffff819d3000-ffffffff819d32cb: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (ffffffff81b4d3a0)
Location: drivers/mfd/rc5t583-irq.c:320
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff81b4d3a0-ffffffff81b4d6e6: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (ffffffff81ba0810)
Location: drivers/mfd/rc5t583-irq.c:320
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff81ba0810-ffffffff81ba0b56: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (ffffffff81bf4970)
Location: drivers/mfd/rc5t583-irq.c:320
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff81bf4970-ffffffff81bf4cb6: rc5t583_irq_init (STB_GLOBAL)
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
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (ffff80001094dd60)
Location: drivers/mfd/rc5t583-irq.c:323
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffff80001094dd60-ffff80001094e00c: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (c0a37de4)
Location: drivers/mfd/rc5t583-irq.c:323
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
c0a37de4-c0a38084: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (c0000000009fa450)
Location: drivers/mfd/rc5t583-irq.c:323
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
c0000000009fa450-c0000000009fa764: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (ffffffe0005bed68)
Location: drivers/mfd/rc5t583-irq.c:323
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffe0005bed68-ffffffe0005befe2: rc5t583_irq_init (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (0)
Location: drivers/mfd/rc5t583-irq.c:323
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff8174238c-ffffffff81742433: rc5t583_irq_init.cold (STB_LOCAL)
ffffffff81742140-ffffffff817422db: rc5t583_irq_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int rc5t583_irq_init(struct rc5t583 *rc5t583, int irq, int irq_base);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mfd/rc5t583-irq.c (0)
Location: drivers/mfd/rc5t583-irq.c:323
Inline: False
Direct callers:
  - drivers/mfd/rc5t583.c:rc5t583_i2c_probe
```
**Symbols:**

```
ffffffff8175d7cc-ffffffff8175d873: rc5t583_irq_init.cold (STB_LOCAL)
ffffffff8175d580-ffffffff8175d71b: rc5t583_irq_init (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
