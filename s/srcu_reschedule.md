# Function: <code>srcu_reschedule</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void srcu_reschedule(struct srcu_struct *sp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810e3e00)
Location: kernel/rcu/srcu.c:637
Inline: True
Direct callers:
  - kernel/rcu/srcu.c:process_srcu
  - kernel/rcu/srcu.c:__synchronize_srcu
  - kernel/rcu/srcu.c:__synchronize_srcu
```
**Symbols:**

```
ffffffff810e3e00-ffffffff810e3eb2: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void srcu_reschedule(struct srcu_struct *sp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810ea100)
Location: kernel/rcu/srcu.c:637
Inline: True
Direct callers:
  - kernel/rcu/srcu.c:process_srcu
  - kernel/rcu/srcu.c:__synchronize_srcu
  - kernel/rcu/srcu.c:__synchronize_srcu
```
**Symbols:**

```
ffffffff810ea100-ffffffff810ea1bc: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void srcu_reschedule(struct srcu_struct *sp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810f0fe0)
Location: kernel/rcu/srcu.c:637
Inline: True
Direct callers:
  - kernel/rcu/srcu.c:process_srcu
  - kernel/rcu/srcu.c:__synchronize_srcu
  - kernel/rcu/srcu.c:__synchronize_srcu
```
**Symbols:**

```
ffffffff810f0fe0-ffffffff810f109c: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void srcu_reschedule(struct srcu_struct *sp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f1740)
Location: kernel/rcu/srcutree.c:1183
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff810f1740-ffffffff810f17d4: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void srcu_reschedule(struct srcu_struct *sp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fb4a0)
Location: kernel/rcu/srcutree.c:1184
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff810fb4a0-ffffffff810fb534: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void srcu_reschedule(struct srcu_struct *sp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81103760)
Location: kernel/rcu/srcutree.c:1214
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff81103760-ffffffff811037fd: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110f2e0)
Location: kernel/rcu/srcutree.c:1232
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff8110f2e0-ffffffff8110f37d: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81119050)
Location: kernel/rcu/srcutree.c:1208
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff81119050-ffffffff811190ed: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81125420)
Location: kernel/rcu/srcutree.c:1209
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff81125420-ffffffff811254bd: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81132c20)
Location: kernel/rcu/srcutree.c:1224
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_gp_end
```
**Symbols:**

```
ffffffff81132c20-ffffffff81132cbd: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e400)
Location: kernel/rcu/srcutree.c:1213
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_gp_end
```
**Symbols:**

```
ffffffff8112e400-ffffffff8112e49d: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112ea20)
Location: kernel/rcu/srcutree.c:1301
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_gp_end
```
**Symbols:**

```
ffffffff8112ea20-ffffffff8112eabd: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8114ff00)
Location: kernel/rcu/srcutree.c:1296
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_gp_end
```
**Symbols:**

```
ffffffff8114ff00-ffffffff8114ff9d: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81176a30)
Location: kernel/rcu/srcutree.c:1591
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff81176a30-ffffffff81176ad3: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811ace10)
Location: kernel/rcu/srcutree.c:1660
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff811ace10-ffffffff811aceb3: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811bed50)
Location: kernel/rcu/srcutree.c:1736
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_gp_end
```
**Symbols:**

```
ffffffff811bed50-ffffffff811bee03: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811cf1c0)
Location: kernel/rcu/srcutree.c:1762
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_gp_end
```
**Symbols:**

```
ffffffff811cf1c0-ffffffff811cf273: srcu_reschedule (STB_LOCAL)
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
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff80001018a2d8)
Location: kernel/rcu/srcutree.c:1209
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffff80001018a2d8-ffff80001018a3f0: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d8f38)
Location: kernel/rcu/srcutree.c:1209
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:srcu_gp_end
```
**Symbols:**

```
c03d8f38-c03d9010: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e5670)
Location: kernel/rcu/srcutree.c:1209
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
c0000000001e5670-c0000000001e57ec: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011f50c)
Location: kernel/rcu/srcutree.c:1209
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffe00011f50c-ffffffe00011f5d8: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111da00)
Location: kernel/rcu/srcutree.c:1209
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff8111da00-ffffffff8111da9d: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110eaa0)
Location: kernel/rcu/srcutree.c:1209
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff8110eaa0-ffffffff8110eb37: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111b8f0)
Location: kernel/rcu/srcutree.c:1209
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff8111b8f0-ffffffff8111b98d: srcu_reschedule (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void srcu_reschedule(struct srcu_struct *ssp, long unsigned int delay);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81126c20)
Location: kernel/rcu/srcutree.c:1209
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:process_srcu
  - kernel/rcu/srcutree.c:process_srcu
```
**Symbols:**

```
ffffffff81126c20-ffffffff81126cb2: srcu_reschedule (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int delay</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct srcu_struct *ssp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct srcu_struct *sp</code>
</li>
</ul>
</details>
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
