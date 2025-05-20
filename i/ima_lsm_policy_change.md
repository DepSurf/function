# Function: <code>ima_lsm_policy_change</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:346
Inline: False
```
**Symbols:**

```
ffffffff8149ff08-ffffffff8149ff1d: ima_lsm_policy_change.cold (STB_LOCAL)
ffffffff8149f510-ffffffff8149f69a: ima_lsm_policy_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:348
Inline: False
```
**Symbols:**

```
ffffffff814ba507-ffffffff814ba51b: ima_lsm_policy_change.cold (STB_LOCAL)
ffffffff814b9ae0-ffffffff814b9c69: ima_lsm_policy_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8151a100)
Location: security/integrity/ima/ima_policy.c:404
Inline: False
```
**Symbols:**

```
ffffffff8151a100-ffffffff8151a11d: ima_lsm_policy_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81537160)
Location: security/integrity/ima/ima_policy.c:463
Inline: False
```
**Symbols:**

```
ffffffff81537160-ffffffff8153717d: ima_lsm_policy_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8153f850)
Location: security/integrity/ima/ima_policy.c:472
Inline: False
```
**Symbols:**

```
ffffffff8153f850-ffffffff8153f86d: ima_lsm_policy_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff8159edc0)
Location: security/integrity/ima/ima_policy.c:484
Inline: False
```
**Symbols:**

```
ffffffff8159edc0-ffffffff8159eddd: ima_lsm_policy_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff816446e0)
Location: security/integrity/ima/ima_policy.c:501
Inline: False
```
**Symbols:**

```
ffffffff816446e0-ffffffff81644709: ima_lsm_policy_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff816fc9e0)
Location: security/integrity/ima/ima_policy.c:522
Inline: False
```
**Symbols:**

```
ffffffff816fc9e0-ffffffff816fcb65: ima_lsm_policy_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff81736a10)
Location: security/integrity/ima/ima_policy.c:522
Inline: False
```
**Symbols:**

```
ffffffff81736a10-ffffffff81736b95: ima_lsm_policy_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffff817774d0)
Location: security/integrity/ima/ima_policy.c:517
Inline: False
```
**Symbols:**

```
ffffffff817774d0-ffffffff81777655: ima_lsm_policy_change (STB_GLOBAL)
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
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffff8000105b1e40)
Location: security/integrity/ima/ima_policy.c:348
Inline: False
```
**Symbols:**

```
ffff8000105b1e40-ffff8000105b2028: ima_lsm_policy_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (c0761500)
Location: security/integrity/ima/ima_policy.c:348
Inline: False
```
**Symbols:**

```
c0761500-c07616a0: ima_lsm_policy_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (c000000000733050)
Location: security/integrity/ima/ima_policy.c:348
Inline: False
```
**Symbols:**

```
c000000000733050-c0000000007332a8: ima_lsm_policy_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/ima/ima_policy.c (ffffffe0003f9796)
Location: security/integrity/ima/ima_policy.c:348
Inline: False
```
**Symbols:**

```
ffffffe0003f9796-ffffffe0003f9920: ima_lsm_policy_change (STB_GLOBAL)
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
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:348
Inline: False
```
**Symbols:**

```
ffffffff814b2ae7-ffffffff814b2afb: ima_lsm_policy_change.cold (STB_LOCAL)
ffffffff814b20c0-ffffffff814b2249: ima_lsm_policy_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:348
Inline: False
```
**Symbols:**

```
ffffffff814a3507-ffffffff814a351b: ima_lsm_policy_change.cold (STB_LOCAL)
ffffffff814a2ae0-ffffffff814a2c69: ima_lsm_policy_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:348
Inline: False
```
**Symbols:**

```
ffffffff814aeb77-ffffffff814aeb8b: ima_lsm_policy_change.cold (STB_LOCAL)
ffffffff814ae150-ffffffff814ae2d9: ima_lsm_policy_change (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ima_lsm_policy_change(struct notifier_block *nb, long unsigned int event, void *lsm_data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/ima/ima_policy.c (0)
Location: security/integrity/ima/ima_policy.c:348
Inline: False
```
**Symbols:**

```
ffffffff814c75e3-ffffffff814c75f7: ima_lsm_policy_change.cold (STB_LOCAL)
ffffffff814c6ba0-ffffffff814c6d29: ima_lsm_policy_change (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
