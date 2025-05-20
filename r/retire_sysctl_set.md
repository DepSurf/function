# Function: <code>retire_sysctl_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812863c0)
Location: fs/proc/proc_sysctl.c:1606
Inline: False
Direct callers:
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff812863c0-ffffffff812863e4: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812b3560)
Location: fs/proc/proc_sysctl.c:1612
Inline: False
Direct callers:
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff812b3560-ffffffff812b3586: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812c8db0)
Location: fs/proc/proc_sysctl.c:1618
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff812c8db0-ffffffff812c8dd6: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812d6120)
Location: fs/proc/proc_sysctl.c:1682
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff812d6120-ffffffff812d6138: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812fa960)
Location: fs/proc/proc_sysctl.c:1683
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff812fa960-ffffffff812fa978: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81327b10)
Location: fs/proc/proc_sysctl.c:1685
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff81327b10-ffffffff81327b27: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8133eca0)
Location: fs/proc/proc_sysctl.c:1685
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff8133eca0-ffffffff8133ecb7: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/proc/proc_sysctl.c (0)
Location: fs/proc/proc_sysctl.c:1712
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff813671fd-ffffffff81367210: retire_sysctl_set.cold (STB_LOCAL)
ffffffff81366fd0-ffffffff81366fe8: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8137f260)
Location: fs/proc/proc_sysctl.c:1712
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff8137f260-ffffffff8137f278: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c92d0)
Location: fs/proc/proc_sysctl.c:1695
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff813c92d0-ffffffff813c92e8: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813db2c0)
Location: fs/proc/proc_sysctl.c:1695
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff813db2c0-ffffffff813db2d8: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813e21f0)
Location: fs/proc/proc_sysctl.c:1699
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff813e21f0-ffffffff813e2208: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81433d00)
Location: fs/proc/proc_sysctl.c:1699
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff81433d00-ffffffff81433d18: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814adcf0)
Location: fs/proc/proc_sysctl.c:1768
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - ipc/ipc_sysctl.c:retire_ipc_sysctls
  - ipc/ipc_sysctl.c:setup_ipc_sysctls
  - ipc/mq_sysctl.c:retire_mq_sysctls
  - ipc/mq_sysctl.c:setup_mq_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff814adcf0-ffffffff814add18: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81544240)
Location: fs/proc/proc_sysctl.c:1767
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - ipc/ipc_sysctl.c:retire_ipc_sysctls
  - ipc/ipc_sysctl.c:setup_ipc_sysctls
  - ipc/mq_sysctl.c:retire_mq_sysctls
  - ipc/mq_sysctl.c:setup_mq_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff81544240-ffffffff81544268: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8157be40)
Location: fs/proc/proc_sysctl.c:1541
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - ipc/ipc_sysctl.c:retire_ipc_sysctls
  - ipc/ipc_sysctl.c:setup_ipc_sysctls
  - ipc/mq_sysctl.c:retire_mq_sysctls
  - ipc/mq_sysctl.c:setup_mq_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff8157be40-ffffffff8157be68: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b46e0)
Location: fs/proc/proc_sysctl.c:1537
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - ipc/ipc_sysctl.c:retire_ipc_sysctls
  - ipc/ipc_sysctl.c:setup_ipc_sysctls
  - ipc/mq_sysctl.c:retire_mq_sysctls
  - ipc/mq_sysctl.c:setup_mq_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff815b46e0-ffffffff815b4708: retire_sysctl_set (STB_GLOBAL)
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
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffff80001044c818)
Location: fs/proc/proc_sysctl.c:1712
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffff80001044c818-ffff80001044c854: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c0611260)
Location: fs/proc/proc_sysctl.c:1712
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
c0611260-c061129c: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c000000000564100)
Location: fs/proc/proc_sysctl.c:1712
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
c000000000564100-c00000000056411c: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffe0002e188a)
Location: fs/proc/proc_sysctl.c:1712
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffe0002e188a-ffffffe0002e18ba: retire_sysctl_set (STB_GLOBAL)
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
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81377840)
Location: fs/proc/proc_sysctl.c:1712
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff81377840-ffffffff81377858: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81368310)
Location: fs/proc/proc_sysctl.c:1712
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff81368310-ffffffff81368328: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81375310)
Location: fs/proc/proc_sysctl.c:1712
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff81375310-ffffffff81375328: retire_sysctl_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void retire_sysctl_set(struct ctl_table_set *set);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81388ce0)
Location: fs/proc/proc_sysctl.c:1712
Inline: False
Direct callers:
  - kernel/ucount.c:retire_userns_sysctls
  - kernel/ucount.c:setup_userns_sysctls
  - net/sysctl_net.c:sysctl_net_exit
```
**Symbols:**

```
ffffffff81388ce0-ffffffff81388cf8: retire_sysctl_set (STB_GLOBAL)
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
