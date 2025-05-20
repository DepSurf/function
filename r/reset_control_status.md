# Function: <code>reset_control_status</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff814df2e0)
Location: drivers/reset/core.c:134
Inline: False
```
**Symbols:**

```
ffffffff814df2e0-ffffffff814df308: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81530210)
Location: drivers/reset/core.c:205
Inline: False
```
**Symbols:**

```
ffffffff81530210-ffffffff81530238: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8155cc50)
Location: drivers/reset/core.c:243
Inline: False
```
**Symbols:**

```
ffffffff8155cc50-ffffffff8155cc9f: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815716c0)
Location: drivers/reset/core.c:264
Inline: True
```
**Symbols:**

```
ffffffff815716c0-ffffffff81571702: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff815d5880)
Location: drivers/reset/core.c:364
Inline: True
```
**Symbols:**

```
ffffffff815d5880-ffffffff815d58d4: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8160e2b0)
Location: drivers/reset/core.c:394
Inline: False
```
**Symbols:**

```
ffffffff8160e2b0-ffffffff8160e303: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8162add0)
Location: drivers/reset/core.c:394
Inline: False
```
**Symbols:**

```
ffffffff8162add0-ffffffff8162ae23: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:446
Inline: False
```
**Symbols:**

```
ffffffff8165f784-ffffffff8165f79c: reset_control_status.cold (STB_LOCAL)
ffffffff8165ec50-ffffffff8165ec9e: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81681340)
Location: drivers/reset/core.c:445
Inline: False
```
**Symbols:**

```
ffffffff81681340-ffffffff81681390: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81732480)
Location: drivers/reset/core.c:446
Inline: False
```
**Symbols:**

```
ffffffff81732480-ffffffff817324d0: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8174e5d0)
Location: drivers/reset/core.c:520
Inline: False
```
**Symbols:**

```
ffffffff8174e5d0-ffffffff8174e620: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff817320b0)
Location: drivers/reset/core.c:604
Inline: False
```
**Symbols:**

```
ffffffff817320b0-ffffffff81732100: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:604
Inline: False
```
**Symbols:**

```
ffffffff81cf84ba-ffffffff81cf84cf: reset_control_status.cold (STB_LOCAL)
ffffffff817b2950-ffffffff817b29b8: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:605
Inline: False
```
**Symbols:**

```
ffffffff81ec05b7-ffffffff81ec05cc: reset_control_status.cold (STB_LOCAL)
ffffffff818ee300-ffffffff818ee371: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:605
Inline: False
```
**Symbols:**

```
ffffffff82094d1d-ffffffff82094d32: reset_control_status.cold (STB_LOCAL)
ffffffff81a45ee0-ffffffff81a45f51: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:605
Inline: False
```
**Symbols:**

```
ffffffff82115b42-ffffffff82115b57: reset_control_status.cold (STB_LOCAL)
ffffffff81a90090-ffffffff81a90102: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/reset/core.c (0)
Location: drivers/reset/core.c:605
Inline: False
```
**Symbols:**

```
ffffffff821f3848-ffffffff821f385d: reset_control_status.cold (STB_LOCAL)
ffffffff81ae2ad0-ffffffff81ae2b42: reset_control_status (STB_GLOBAL)
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
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffff80001084c228)
Location: drivers/reset/core.c:445
Inline: False
```
**Symbols:**

```
ffff80001084c228-ffff80001084c2a4: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0958564)
Location: drivers/reset/core.c:445
Inline: False
```
**Symbols:**

```
c0958564-c09585f0: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (c0000000008ea860)
Location: drivers/reset/core.c:445
Inline: False
```
**Symbols:**

```
c0000000008ea860-c0000000008ea918: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffe00052bae0)
Location: drivers/reset/core.c:445
Inline: False
```
**Symbols:**

```
ffffffe00052bae0-ffffffe00052bb38: reset_control_status (STB_GLOBAL)
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
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81646dc0)
Location: drivers/reset/core.c:445
Inline: False
```
**Symbols:**

```
ffffffff81646dc0-ffffffff81646e10: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81627220)
Location: drivers/reset/core.c:445
Inline: False
```
**Symbols:**

```
ffffffff81627220-ffffffff81627270: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff81675180)
Location: drivers/reset/core.c:445
Inline: False
```
**Symbols:**

```
ffffffff81675180-ffffffff816751d0: reset_control_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int reset_control_status(struct reset_control *rstc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/reset/core.c (ffffffff8168f7e0)
Location: drivers/reset/core.c:445
Inline: False
```
**Symbols:**

```
ffffffff8168f7e0-ffffffff8168f830: reset_control_status (STB_GLOBAL)
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
