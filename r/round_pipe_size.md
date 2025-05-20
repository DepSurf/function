# Function: <code>round_pipe_size</code>

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
In fs/pipe.c (ffffffff8121601e)
Location: fs/pipe.c:1050
Inline: True
Inline callers:
  - fs/pipe.c:pipe_proc_fn
  - fs/pipe.c:pipe_fcntl
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
In fs/pipe.c (ffffffff8123cf3b)
Location: fs/pipe.c:1068
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_proc_fn
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
In fs/pipe.c (ffffffff8124fc9c)
Location: fs/pipe.c:1023
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_proc_fn
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
In fs/pipe.c (ffffffff8125bbfe)
Location: fs/pipe.c:1022
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:pipe_proc_fn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int round_pipe_size(unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8127dee0)
Location: fs/pipe.c:1028
Inline: False
Direct callers:
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff8127dee0-ffffffff8127df25: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff812a4f1e)
Location: fs/pipe.c:1033
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff812a3a40-ffffffff812a3a63: round_pipe_size.part.9 (STB_LOCAL)
ffffffff812a4e50-ffffffff812a4e7b: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff812b9fee)
Location: fs/pipe.c:1026
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff812b8b90-ffffffff812b8bb3: round_pipe_size.part.9 (STB_LOCAL)
ffffffff812b9f20-ffffffff812b9f4b: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff812d6c7c)
Location: fs/pipe.c:1038
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff812d5710-ffffffff812d5733: round_pipe_size.part.0 (STB_LOCAL)
ffffffff812d6bb0-ffffffff812d6bdb: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff812e87ec)
Location: fs/pipe.c:1038
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff812e7280-ffffffff812e72a3: round_pipe_size.part.0 (STB_LOCAL)
ffffffff812e8720-ffffffff812e874b: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff81320a50)
Location: fs/pipe.c:1216
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff8131ebf0-ffffffff8131ec13: round_pipe_size.part.0 (STB_LOCAL)
ffffffff81320810-ffffffff8132083b: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8132bd80)
Location: fs/pipe.c:1216
Inline: True
Direct callers:
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff8132bd80-ffffffff8132bdbd: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff81331dc0)
Location: fs/pipe.c:1230
Inline: True
Direct callers:
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff81331dc0-ffffffff81331dfd: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff8137f55f)
Location: fs/pipe.c:1233
Inline: True
Direct callers:
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff81cc3a4a-ffffffff81cc3a72: round_pipe_size.cold (STB_LOCAL)
ffffffff8137f540-ffffffff8137f582: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff813fe25b)
Location: fs/pipe.c:1234
Inline: True
Inline callers:
  - fs/pipe.c:do_proc_dopipe_max_size_conv
Direct callers:
  - fs/pipe.c:do_proc_dopipe_max_size_conv
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff813fd8f0-ffffffff813fd923: round_pipe_size.part.0 (STB_LOCAL)
ffffffff81e76213-ffffffff81e76247: round_pipe_size.part.0.cold (STB_LOCAL)
ffffffff81e7625b-ffffffff81e7628f: round_pipe_size.cold (STB_LOCAL)
ffffffff813ff640-ffffffff813ff69a: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff81487eab)
Location: fs/pipe.c:1234
Inline: True
Inline callers:
  - fs/pipe.c:do_proc_dopipe_max_size_conv
Direct callers:
  - fs/pipe.c:do_proc_dopipe_max_size_conv
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff81487500-ffffffff81487533: round_pipe_size.part.0 (STB_LOCAL)
ffffffff8206881d-ffffffff82068851: round_pipe_size.part.0.cold (STB_LOCAL)
ffffffff82068865-ffffffff82068899: round_pipe_size.cold (STB_LOCAL)
ffffffff81489410-ffffffff8148946a: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff814bcd8b)
Location: fs/pipe.c:1239
Inline: True
Inline callers:
  - fs/pipe.c:do_proc_dopipe_max_size_conv
Direct callers:
  - fs/pipe.c:do_proc_dopipe_max_size_conv
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff814bc310-ffffffff814bc343: round_pipe_size.part.0 (STB_LOCAL)
ffffffff820e8118-ffffffff820e814c: round_pipe_size.part.0.cold (STB_LOCAL)
ffffffff820e8160-ffffffff820e8194: round_pipe_size.cold (STB_LOCAL)
ffffffff814be340-ffffffff814be39a: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int round_pipe_size(unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff814ef23d)
Location: fs/pipe.c:1255
Inline: True
Inline callers:
  - fs/pipe.c:do_proc_dopipe_max_size_conv
Direct callers:
  - fs/pipe.c:do_proc_dopipe_max_size_conv
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff814ee840-ffffffff814ee875: round_pipe_size.part.0 (STB_LOCAL)
ffffffff821c4e54-ffffffff821c4e88: round_pipe_size.part.0.cold (STB_LOCAL)
ffffffff821c4e9d-ffffffff821c4ed1: round_pipe_size.cold (STB_LOCAL)
ffffffff814f07c0-ffffffff814f0819: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffff800010391868)
Location: fs/pipe.c:1038
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffff80001038fb08-ffff80001038fb48: round_pipe_size.part.0 (STB_LOCAL)
ffff800010391720-ffff800010391774: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (c057811c)
Location: fs/pipe.c:1038
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
c05769a8-c05769d4: round_pipe_size.part.0 (STB_LOCAL)
c057802c-c0578068: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (c0000000004898f0)
Location: fs/pipe.c:1038
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
c0000000004877f0-c000000000487814: round_pipe_size.part.0 (STB_LOCAL)
c0000000004897b0-c0000000004897f8: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffe000260d16)
Location: fs/pipe.c:1038
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffe00025fa34-ffffffe00025fa98: round_pipe_size.part.0 (STB_LOCAL)
ffffffe000260c2a-ffffffe000260c66: round_pipe_size (STB_GLOBAL)
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
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff812e0dcc)
Location: fs/pipe.c:1038
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff812df860-ffffffff812df883: round_pipe_size.part.0 (STB_LOCAL)
ffffffff812e0d00-ffffffff812e0d2b: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff812d1a0c)
Location: fs/pipe.c:1038
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff812d04a0-ffffffff812d04c3: round_pipe_size.part.0 (STB_LOCAL)
ffffffff812d1940-ffffffff812d196b: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff812debdc)
Location: fs/pipe.c:1038
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff812dd670-ffffffff812dd693: round_pipe_size.part.0 (STB_LOCAL)
ffffffff812deb10-ffffffff812deb3b: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int round_pipe_size(long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/pipe.c (ffffffff812efb4c)
Location: fs/pipe.c:1038
Inline: True
Inline callers:
  - fs/pipe.c:pipe_fcntl
Direct callers:
  - fs/pipe.c:pipe_fcntl
```
**Symbols:**

```
ffffffff812ee5f0-ffffffff812ee613: round_pipe_size.part.0 (STB_LOCAL)
ffffffff812efa80-ffffffff812efaab: round_pipe_size (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int size</code> ➡️ <code>long unsigned int size</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int size</code> ➡️ <code>unsigned int size</code>
</li>
</ul>
</details>
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
