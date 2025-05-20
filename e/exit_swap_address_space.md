# Function: <code>exit_swap_address_space</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8120c5b0)
Location: mm/swap_state.c:554
Inline: False
Direct callers:
  - mm/swapfile.c:SyS_swapoff
```
**Symbols:**

```
ffffffff8120c5b0-ffffffff8120c5eb: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81225d20)
Location: mm/swap_state.c:628
Inline: False
Direct callers:
  - mm/swapfile.c:SYSC_swapoff
```
**Symbols:**

```
ffffffff81225d20-ffffffff81225d5b: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81248330)
Location: mm/swap_state.c:640
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff81248330-ffffffff8124836b: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8125c900)
Location: mm/swap_state.c:602
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff8125c900-ffffffff8125c93b: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81277ae0)
Location: mm/swap_state.c:620
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff81277ae0-ffffffff81277b13: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812875d0)
Location: mm/swap_state.c:620
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff812875d0-ffffffff81287603: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812b9e20)
Location: mm/swap_state.c:638
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff812b9e20-ffffffff812b9e56: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812c5890)
Location: mm/swap_state.c:730
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff812c5890-ffffffff812c58c6: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812cc550)
Location: mm/swap_state.c:699
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff812cc550-ffffffff812cc57b: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81311790)
Location: mm/swap_state.c:687
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff81311790-ffffffff81311864: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8137c8d0)
Location: mm/swap_state.c:700
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff8137c8d0-ffffffff8137c9af: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff813fa0b0)
Location: mm/swap_state.c:684
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff813fa0b0-ffffffff813fa18f: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8142cfe0)
Location: mm/swap_state.c:699
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff8142cfe0-ffffffff8142d0bf: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff814666f0)
Location: mm/swap_state.c:713
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapon
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff814666f0-ffffffff814667cf: exit_swap_address_space (STB_GLOBAL)
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
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffff800010322160)
Location: mm/swap_state.c:620
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffff800010322160-ffff8000103221ac: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c053a7f8)
Location: mm/swap_state.c:620
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
c053a7f8-c053a830: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (c0000000003f7b30)
Location: mm/swap_state.c:620
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
c0000000003f7b30-c0000000003f7bac: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffe00022318a)
Location: mm/swap_state.c:620
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffe00022318a-ffffffe0002231dc: exit_swap_address_space (STB_GLOBAL)
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
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127fba0)
Location: mm/swap_state.c:579
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff8127fba0-ffffffff8127fbd3: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81271a40)
Location: mm/swap_state.c:620
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff81271a40-ffffffff81271a73: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8127d9c0)
Location: mm/swap_state.c:620
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff8127d9c0-ffffffff8127d9f3: exit_swap_address_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void exit_swap_address_space(unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8128d570)
Location: mm/swap_state.c:620
Inline: False
Direct callers:
  - mm/swapfile.c:__do_sys_swapoff
```
**Symbols:**

```
ffffffff8128d570-ffffffff8128d5a3: exit_swap_address_space (STB_GLOBAL)
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
