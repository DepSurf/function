# Function: <code>extcon_set_state_sync</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool cable_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81780070)
Location: drivers/extcon/extcon.c:579
Inline: False
```
**Symbols:**

```
ffffffff81780070-ffffffff8178012d: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool cable_state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8179e600)
Location: drivers/extcon/extcon.c:593
Inline: False
```
**Symbols:**

```
ffffffff8179e600-ffffffff8179e6c1: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81815760)
Location: drivers/extcon/extcon.c:584
Inline: False
```
**Symbols:**

```
ffffffff81815760-ffffffff81815821: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8185f650)
Location: drivers/extcon/extcon.c:585
Inline: False
```
**Symbols:**

```
ffffffff8185f650-ffffffff8185f710: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8187eff0)
Location: drivers/extcon/extcon.c:585
Inline: False
```
**Symbols:**

```
ffffffff8187eff0-ffffffff8187f0b0: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818c9600)
Location: drivers/extcon/extcon.c:577
Inline: False
```
**Symbols:**

```
ffffffff818c9600-ffffffff818c96b0: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818fba50)
Location: drivers/extcon/extcon.c:577
Inline: False
```
**Symbols:**

```
ffffffff818fba50-ffffffff818fbb00: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d26e0)
Location: drivers/extcon/extcon.c:577
Inline: False
```
**Symbols:**

```
ffffffff819d26e0-ffffffff819d27a7: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d22c0)
Location: drivers/extcon/extcon.c:577
Inline: False
```
**Symbols:**

```
ffffffff819d22c0-ffffffff819d2387: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819b7580)
Location: drivers/extcon/extcon.c:577
Inline: False
```
**Symbols:**

```
ffffffff819b7580-ffffffff819b7647: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (0)
Location: drivers/extcon/extcon.c:577
Inline: False
```
**Symbols:**

```
ffffffff81d335fd-ffffffff81d33626: extcon_set_state_sync.cold (STB_LOCAL)
ffffffff81a662b0-ffffffff81a6638e: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81bd76e0)
Location: drivers/extcon/extcon.c:578
Inline: False
```
**Symbols:**

```
ffffffff81bd76e0-ffffffff81bd772d: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81d84030)
Location: drivers/extcon/extcon.c:588
Inline: False
```
**Symbols:**

```
ffffffff81d84030-ffffffff81d8407d: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81df23f0)
Location: drivers/extcon/extcon.c:598
Inline: False
```
**Symbols:**

```
ffffffff81df23f0-ffffffff81df243d: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81ea8a40)
Location: drivers/extcon/extcon.c:598
Inline: False
```
**Symbols:**

```
ffffffff81ea8a40-ffffffff81ea8a8d: extcon_set_state_sync (STB_GLOBAL)
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
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffff800010b89638)
Location: drivers/extcon/extcon.c:577
Inline: True
```
**Symbols:**

```
ffff800010b89638-ffff800010b89788: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (c0c6d0e0)
Location: drivers/extcon/extcon.c:577
Inline: True
```
**Symbols:**

```
c0c6d0e0-c0c6d1a0: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (c000000000c682b0)
Location: drivers/extcon/extcon.c:577
Inline: True
```
**Symbols:**

```
c000000000c682b0-c000000000c6843c: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffe0007317d0)
Location: drivers/extcon/extcon.c:577
Inline: True
```
**Symbols:**

```
ffffffe0007317d0-ffffffe000731872: extcon_set_state_sync (STB_GLOBAL)
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
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8189cd80)
Location: drivers/extcon/extcon.c:577
Inline: False
```
**Symbols:**

```
ffffffff8189cd80-ffffffff8189ce30: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818ec470)
Location: drivers/extcon/extcon.c:577
Inline: False
```
**Symbols:**

```
ffffffff818ec470-ffffffff818ec520: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int extcon_set_state_sync(struct extcon_dev *edev, unsigned int id, bool state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8190d4f0)
Location: drivers/extcon/extcon.c:577
Inline: False
```
**Symbols:**

```
ffffffff8190d4f0-ffffffff8190d5a0: extcon_set_state_sync (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool state</code>
</li>
<li>
<b>Param removed. </b>
<code>bool cable_state</code>
</li>
</ul>
</details>
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
