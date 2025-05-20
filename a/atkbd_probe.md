# Function: <code>atkbd_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff81670050)
Location: drivers/input/keyboard/atkbd.c:724
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_connect
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
```
**Symbols:**

```
ffffffff81670050-ffffffff816701bc: atkbd_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff816d03a0)
Location: drivers/input/keyboard/atkbd.c:724
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff816d03a0-ffffffff816d050e: atkbd_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff816fe280)
Location: drivers/input/keyboard/atkbd.c:724
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff816fe280-ffffffff816fe3ee: atkbd_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff81713770)
Location: drivers/input/keyboard/atkbd.c:724
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff81713770-ffffffff817138df: atkbd_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff817849b0)
Location: drivers/input/keyboard/atkbd.c:724
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff817849b0-ffffffff81784b1f: atkbd_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff817c5a80)
Location: drivers/input/keyboard/atkbd.c:724
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff817c5a80-ffffffff817c5be5: atkbd_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff817ed050)
Location: drivers/input/keyboard/atkbd.c:724
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff817ed050-ffffffff817ed1b5: atkbd_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:722
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff8182dc10-ffffffff8182dd33: atkbd_probe (STB_LOCAL)
ffffffff8182f287-ffffffff8182f2e4: atkbd_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:722
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff8185f540-ffffffff8185f663: atkbd_probe (STB_LOCAL)
ffffffff81860bb7-ffffffff81860c14: atkbd_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:763
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff81931f00-ffffffff81932015: atkbd_probe (STB_LOCAL)
ffffffff81933d73-ffffffff81933dd0: atkbd_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:763
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff81939160-ffffffff81939275: atkbd_probe (STB_LOCAL)
ffffffff81c23556-ffffffff81c235b3: atkbd_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:763
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff8191c880-ffffffff8191c995: atkbd_probe (STB_LOCAL)
ffffffff81c1562c-ffffffff81c15689: atkbd_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:763
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff819bf1f0-ffffffff819bf336: atkbd_probe (STB_LOCAL)
ffffffff81d23ae6-ffffffff81d23b83: atkbd_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:751
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff81b1f470-ffffffff81b1f5c5: atkbd_probe (STB_LOCAL)
ffffffff81eef8fb-ffffffff81eef993: atkbd_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:753
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff81cb1610-ffffffff81cb17b2: atkbd_probe (STB_LOCAL)
ffffffff820a6e17-ffffffff820a6e56: atkbd_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:772
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff81d18c70-ffffffff81d18e16: atkbd_probe (STB_LOCAL)
ffffffff82128222-ffffffff82128261: atkbd_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:810
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff81dce920-ffffffff81dceb36: atkbd_probe (STB_LOCAL)
ffffffff82209ba3-ffffffff82209bf3: atkbd_probe.cold (STB_LOCAL)
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
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffff800010aa17a0)
Location: drivers/input/keyboard/atkbd.c:722
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffff800010aa17a0-ffff800010aa1910: atkbd_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (c0b8161c)
Location: drivers/input/keyboard/atkbd.c:722
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
c0b8161c-c0b817a8: atkbd_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (c000000000b82230)
Location: drivers/input/keyboard/atkbd.c:722
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
c000000000b82230-c000000000b82410: atkbd_probe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffe0006af8d8)
Location: drivers/input/keyboard/atkbd.c:722
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffe0006af8d8-ffffffe0006af9f0: atkbd_probe (STB_LOCAL)
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
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:722
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff81814550-ffffffff81814673: atkbd_probe (STB_LOCAL)
ffffffff81815bc7-ffffffff81815c24: atkbd_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:722
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff817dbc80-ffffffff817dbda3: atkbd_probe (STB_LOCAL)
ffffffff817dd2c7-ffffffff817dd324: atkbd_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:722
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff818536d0-ffffffff818537f3: atkbd_probe (STB_LOCAL)
ffffffff81854d47-ffffffff81854da4: atkbd_probe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int atkbd_probe(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:722
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_reconnect
  - drivers/input/keyboard/atkbd.c:atkbd_connect
```
**Symbols:**

```
ffffffff8186eaa0-ffffffff8186ebc3: atkbd_probe (STB_LOCAL)
ffffffff8186fe71-ffffffff8186fece: atkbd_probe.cold (STB_LOCAL)
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
