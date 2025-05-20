# Function: <code>sysrq_toggle_support</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff814ee3e0)
Location: drivers/tty/sysrq.c:1027
Inline: False
```
**Symbols:**

```
ffffffff814ee3e0-ffffffff814ee477: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff8153f020)
Location: drivers/tty/sysrq.c:1034
Inline: False
```
**Symbols:**

```
ffffffff8153f020-ffffffff8153f0a6: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff8156b670)
Location: drivers/tty/sysrq.c:1034
Inline: False
```
**Symbols:**

```
ffffffff8156b670-ffffffff8156b6f6: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff8157fd10)
Location: drivers/tty/sysrq.c:1043
Inline: False
```
**Symbols:**

```
ffffffff8157fd10-ffffffff8157fd9a: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff815e4890)
Location: drivers/tty/sysrq.c:1048
Inline: False
```
**Symbols:**

```
ffffffff815e4890-ffffffff815e491a: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:1048
Inline: False
```
**Symbols:**

```
ffffffff8161dc11-ffffffff8161dc24: sysrq_toggle_support.cold.10 (STB_LOCAL)
ffffffff8161da00-ffffffff8161da7b: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:1042
Inline: False
```
**Symbols:**

```
ffffffff8163ae76-ffffffff8163ae89: sysrq_toggle_support.cold.10 (STB_LOCAL)
ffffffff8163ac50-ffffffff8163accb: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:1048
Inline: False
```
**Symbols:**

```
ffffffff8166f1f7-ffffffff8166f20a: sysrq_toggle_support.cold (STB_LOCAL)
ffffffff8166efd0-ffffffff8166f04b: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:1041
Inline: False
```
**Symbols:**

```
ffffffff816917d7-ffffffff816917ea: sysrq_toggle_support.cold (STB_LOCAL)
ffffffff816915d0-ffffffff8169164b: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:1049
Inline: True
Direct callers:
  - kernel/sysctl.c:sysrq_sysctl_handler
```
**Symbols:**

```
ffffffff81743e7f-ffffffff81743e92: sysrq_toggle_support.cold (STB_LOCAL)
ffffffff817438e0-ffffffff81743944: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:1092
Inline: True
Direct callers:
  - kernel/sysctl.c:sysrq_sysctl_handler
```
**Symbols:**

```
ffffffff81c0777d-ffffffff81c07790: sysrq_toggle_support.cold (STB_LOCAL)
ffffffff8175f690-ffffffff8175f6f4: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:1093
Inline: True
Direct callers:
  - kernel/sysctl.c:sysrq_sysctl_handler
```
**Symbols:**

```
ffffffff81bf93e7-ffffffff81bf93fa: sysrq_toggle_support.cold (STB_LOCAL)
ffffffff81743500-ffffffff81743564: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:1093
Inline: True
Direct callers:
  - kernel/sysctl.c:sysrq_sysctl_handler
```
**Symbols:**

```
ffffffff81cf8e77-ffffffff81cf8ef2: sysrq_toggle_support.cold (STB_LOCAL)
ffffffff817c4140-ffffffff817c41d5: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:1098
Inline: True
Direct callers:
  - kernel/sysctl.c:sysrq_sysctl_handler
```
**Symbols:**

```
ffffffff81ec0fcc-ffffffff81ec105f: sysrq_toggle_support.cold (STB_LOCAL)
ffffffff81900e30-ffffffff81900ee4: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:1098
Inline: True
Direct callers:
  - kernel/sysctl.c:sysrq_sysctl_handler
```
**Symbols:**

```
ffffffff820953d3-ffffffff82095453: sysrq_toggle_support.cold (STB_LOCAL)
ffffffff81a5ab10-ffffffff81a5abbf: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:1098
Inline: True
Direct callers:
  - kernel/sysctl.c:sysrq_sysctl_handler
```
**Symbols:**

```
ffffffff82116222-ffffffff821162a2: sysrq_toggle_support.cold (STB_LOCAL)
ffffffff81aa5140-ffffffff81aa51ef: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:1097
Inline: True
Direct callers:
  - kernel/sysctl.c:sysrq_sysctl_handler
```
**Symbols:**

```
ffffffff821f3f34-ffffffff821f3fb4: sysrq_toggle_support.cold (STB_LOCAL)
ffffffff81af7b80-ffffffff81af7c2f: sysrq_toggle_support (STB_GLOBAL)
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
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffff800010864c78)
Location: drivers/tty/sysrq.c:1041
Inline: False
```
**Symbols:**

```
ffff800010864c78-ffff800010864e3c: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (c096a558)
Location: drivers/tty/sysrq.c:1041
Inline: False
```
**Symbols:**

```
c096a558-c096a730: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (c000000000903ed0)
Location: drivers/tty/sysrq.c:1041
Inline: False
```
**Symbols:**

```
c000000000903ed0-c000000000904160: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffe00053b254)
Location: drivers/tty/sysrq.c:1041
Inline: False
```
**Symbols:**

```
ffffffe00053b254-ffffffe00053b3ea: sysrq_toggle_support (STB_GLOBAL)
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
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:1041
Inline: False
```
**Symbols:**

```
ffffffff81657257-ffffffff8165726a: sysrq_toggle_support.cold (STB_LOCAL)
ffffffff81657050-ffffffff816570cb: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:1041
Inline: False
```
**Symbols:**

```
ffffffff816375e7-ffffffff816375fa: sysrq_toggle_support.cold (STB_LOCAL)
ffffffff816373e0-ffffffff8163745b: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:1041
Inline: False
```
**Symbols:**

```
ffffffff81685617-ffffffff8168562a: sysrq_toggle_support.cold (STB_LOCAL)
ffffffff81685410-ffffffff8168548b: sysrq_toggle_support (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sysrq_toggle_support(int enable_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/sysrq.c (0)
Location: drivers/tty/sysrq.c:1041
Inline: False
```
**Symbols:**

```
ffffffff8169fc1c-ffffffff8169fc2f: sysrq_toggle_support.cold (STB_LOCAL)
ffffffff8169fa10-ffffffff8169fa8b: sysrq_toggle_support (STB_GLOBAL)
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
