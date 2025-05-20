# Function: <code>genpd_sync_power_off</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff815f37f0)
Location: drivers/base/power/domain.c:762
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff815f37f0-ffffffff815f38d4: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8165b5f0)
Location: drivers/base/power/domain.c:880
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff8165b5f0-ffffffff8165b6e0: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816972a0)
Location: drivers/base/power/domain.c:881
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff816972a0-ffffffff8169738c: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b7f80)
Location: drivers/base/power/domain.c:960
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff816b7f80-ffffffff816b806c: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816f1cb0)
Location: drivers/base/power/domain.c:963
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff816f1cb0-ffffffff816f1daf: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81716430)
Location: drivers/base/power/domain.c:958
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff81716430-ffffffff8171652f: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817d1750)
Location: drivers/base/power/domain.c:947
Inline: True
Direct callers:
  - drivers/base/power/domain.c:pm_genpd_syscore_poweroff
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff817d1750-ffffffff817d184f: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817e5f00)
Location: drivers/base/power/domain.c:993
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff817e5f00-ffffffff817e6008: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff817ca310)
Location: drivers/base/power/domain.c:1024
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff817ca310-ffffffff817ca418: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81855930)
Location: drivers/base/power/domain.c:1064
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff81855930-ffffffff81855a44: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8199a9e0)
Location: drivers/base/power/domain.c:1075
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff8199a9e0-ffffffff8199ab4d: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b0dff0)
Location: drivers/base/power/domain.c:1096
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff81b0dff0-ffffffff81b0e15d: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81b5c0a0)
Location: drivers/base/power/domain.c:1122
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_switch_state
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff81b5c0a0-ffffffff81b5c20d: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pmdomain/core.c (ffffffff81aa3ba0)
Location: drivers/pmdomain/core.c:1129
Inline: True
Direct callers:
  - drivers/pmdomain/core.c:genpd_switch_state
  - drivers/pmdomain/core.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff81aa3ba0-ffffffff81aa3d0d: genpd_sync_power_off (STB_LOCAL)
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
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffff800010908e58)
Location: drivers/base/power/domain.c:958
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffff800010908e58-ffff800010908f6c: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c09f2970)
Location: drivers/base/power/domain.c:958
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
c09f2970-c09f2a84: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (c0000000009a7cd0)
Location: drivers/base/power/domain.c:958
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
c0000000009a7cd0-c0000000009a7e4c: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816dc760)
Location: drivers/base/power/domain.c:958
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff816dc760-ffffffff816dc85f: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff816b6de0)
Location: drivers/base/power/domain.c:958
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff816b6de0-ffffffff816b6edf: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff8170a0f0)
Location: drivers/base/power/domain.c:958
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff8170a0f0-ffffffff8170a1ef: genpd_sync_power_off (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void genpd_sync_power_off(struct generic_pm_domain *genpd, bool use_lock, unsigned int depth);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/power/domain.c (ffffffff81724df0)
Location: drivers/base/power/domain.c:958
Inline: True
Direct callers:
  - drivers/base/power/domain.c:genpd_syscore_switch
  - drivers/base/power/domain.c:genpd_finish_suspend
```
**Symbols:**

```
ffffffff81724df0-ffffffff81724eef: genpd_sync_power_off (STB_LOCAL)
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
