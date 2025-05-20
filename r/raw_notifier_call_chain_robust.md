# Function: <code>raw_notifier_call_chain_robust</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int raw_notifier_call_chain_robust(struct raw_notifier_head *nh, long unsigned int val_up, long unsigned int val_down, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d1ad0)
Location: kernel/notifier.c:383
Inline: False
Direct callers:
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
```
**Symbols:**

```
ffffffff810d1ad0-ffffffff810d1b8a: raw_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int raw_notifier_call_chain_robust(struct raw_notifier_head *nh, long unsigned int val_up, long unsigned int val_down, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810d36b0)
Location: kernel/notifier.c:383
Inline: False
Direct callers:
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
```
**Symbols:**

```
ffffffff810d36b0-ffffffff810d376a: raw_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int raw_notifier_call_chain_robust(struct raw_notifier_head *nh, long unsigned int val_up, long unsigned int val_down, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff810e6910)
Location: kernel/notifier.c:364
Inline: False
Direct callers:
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
```
**Symbols:**

```
ffffffff810e6910-ffffffff810e69ca: raw_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int raw_notifier_call_chain_robust(struct raw_notifier_head *nh, long unsigned int val_up, long unsigned int val_down, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81100910)
Location: kernel/notifier.c:428
Inline: False
Direct callers:
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - net/core/dev.c:netdev_offload_xstats_enable
```
**Symbols:**

```
ffffffff81100910-ffffffff811009d0: raw_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int raw_notifier_call_chain_robust(struct raw_notifier_head *nh, long unsigned int val_up, long unsigned int val_down, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81125880)
Location: kernel/notifier.c:428
Inline: False
Direct callers:
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - net/core/dev.c:netdev_offload_xstats_enable
```
**Symbols:**

```
ffffffff81125880-ffffffff81125940: raw_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int raw_notifier_call_chain_robust(struct raw_notifier_head *nh, long unsigned int val_up, long unsigned int val_down, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff81132e20)
Location: kernel/notifier.c:434
Inline: False
Direct callers:
  - drivers/base/power/domain.c:_genpd_power_off
  - drivers/base/power/domain.c:_genpd_power_on
  - net/core/dev.c:netdev_offload_xstats_enable
```
**Symbols:**

```
ffffffff81132e20-ffffffff81132eb6: raw_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int raw_notifier_call_chain_robust(struct raw_notifier_head *nh, long unsigned int val_up, long unsigned int val_down, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/notifier.c (ffffffff8113dd30)
Location: kernel/notifier.c:434
Inline: False
Direct callers:
  - drivers/pmdomain/core.c:_genpd_power_off
  - drivers/pmdomain/core.c:_genpd_power_on
  - net/core/dev.c:netdev_offload_xstats_enable
```
**Symbols:**

```
ffffffff8113dd30-ffffffff8113ddc6: raw_notifier_call_chain_robust (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
