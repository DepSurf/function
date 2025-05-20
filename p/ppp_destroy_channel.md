# Function: <code>ppp_destroy_channel</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff815f4f10)
Location: drivers/net/ppp/ppp_generic.c:2979
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_release
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
```
**Symbols:**

```
ffffffff815f4f10-ffffffff815f4f59: ppp_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81654c70)
Location: drivers/net/ppp/ppp_generic.c:3134
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff81654c70-ffffffff81654cd6: ppp_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81682960)
Location: drivers/net/ppp/ppp_generic.c:3173
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff81682960-ffffffff816829c6: ppp_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81697d70)
Location: drivers/net/ppp/ppp_generic.c:3188
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff81697d70-ffffffff81697dd6: ppp_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81702c60)
Location: drivers/net/ppp/ppp_generic.c:3224
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff81702c60-ffffffff81702cc6: ppp_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:3207
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff81741830-ffffffff81741891: ppp_destroy_channel (STB_LOCAL)
ffffffff81745c97-ffffffff81745cab: ppp_destroy_channel.cold.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:3255
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff81765940-ffffffff817659a1: ppp_destroy_channel (STB_LOCAL)
ffffffff81769d87-ffffffff81769d9b: ppp_destroy_channel.cold.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:3251
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff817a3970-ffffffff817a39d6: ppp_destroy_channel (STB_LOCAL)
ffffffff817a79ef-ffffffff817a7a03: ppp_destroy_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:3251
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff817c73c0-ffffffff817c7426: ppp_destroy_channel (STB_LOCAL)
ffffffff817cb45f-ffffffff817cb473: ppp_destroy_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:3335
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff81891ce0-ffffffff81891d64: ppp_destroy_channel (STB_LOCAL)
ffffffff81895887-ffffffff8189589b: ppp_destroy_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:3487
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_bridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff818a0020-ffffffff818a00aa: ppp_destroy_channel (STB_LOCAL)
ffffffff81c1995f-ffffffff81c19973: ppp_destroy_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:3520
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff81882b30-ffffffff81882bba: ppp_destroy_channel (STB_LOCAL)
ffffffff81c0b7b6-ffffffff81c0b7ca: ppp_destroy_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:3525
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff819144d0-ffffffff8191455a: ppp_destroy_channel (STB_LOCAL)
ffffffff81d10dfb-ffffffff81d10e0f: ppp_destroy_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81edbb5a)
Location: drivers/net/ppp/ppp_generic.c:3526
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff81a69ac0-ffffffff81a69b50: ppp_destroy_channel (STB_LOCAL)
ffffffff81edbb5a-ffffffff81edbb6e: ppp_destroy_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfc650)
Location: drivers/net/ppp/ppp_generic.c:3528
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff81bfc650-ffffffff81bfc700: ppp_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81c61cd0)
Location: drivers/net/ppp/ppp_generic.c:3528
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff81c61cd0-ffffffff81c61d80: ppp_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81d186c0)
Location: drivers/net/ppp/ppp_generic.c:3528
Inline: True
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_ioctl
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_unbridge_channels
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff81d186c0-ffffffff81d1877a: ppp_destroy_channel (STB_LOCAL)
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
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffff8000109fe7c8)
Location: drivers/net/ppp/ppp_generic.c:3251
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffff8000109fe7c8-ffff8000109fe87c: ppp_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c0adc1b4)
Location: drivers/net/ppp/ppp_generic.c:3251
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
c0adc1b4-c0adc254: ppp_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c000000000aa6520)
Location: drivers/net/ppp/ppp_generic.c:3251
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
c000000000aa6520-c000000000aa6604: ppp_destroy_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffe00062bec8)
Location: drivers/net/ppp/ppp_generic.c:3251
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffe00062bec8-ffffffe00062bf52: ppp_destroy_channel (STB_LOCAL)
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
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:3251
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff8178bea0-ffffffff8178bf06: ppp_destroy_channel (STB_LOCAL)
ffffffff8178ff3f-ffffffff8178ff53: ppp_destroy_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:3251
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff81774c70-ffffffff81774cd6: ppp_destroy_channel (STB_LOCAL)
ffffffff81778d0f-ffffffff81778d23: ppp_destroy_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:3251
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff817bc240-ffffffff817bc2a6: ppp_destroy_channel (STB_LOCAL)
ffffffff817c02df-ffffffff817c02f3: ppp_destroy_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ppp_destroy_channel(struct channel *pch);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (0)
Location: drivers/net/ppp/ppp_generic.c:3251
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_unregister_channel
  - drivers/net/ppp/ppp_generic.c:ppp_release
```
**Symbols:**

```
ffffffff817d65e0-ffffffff817d6646: ppp_destroy_channel (STB_LOCAL)
ffffffff817da592-ffffffff817da5a6: ppp_destroy_channel.cold (STB_LOCAL)
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
