# Function: <code>srcu_funnel_gp_start</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f1f01)
Location: kernel/rcu/srcutree.c:613
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fbc74)
Location: kernel/rcu/srcutree.c:614
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110416e)
Location: kernel/rcu/srcutree.c:645
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110fb67)
Location: kernel/rcu/srcutree.c:656
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81118a3b)
Location: kernel/rcu/srcutree.c:631
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81124e0b)
Location: kernel/rcu/srcutree.c:631
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void srcu_funnel_gp_start(struct srcu_struct *ssp, struct srcu_data *sdp, long unsigned int s, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81132680)
Location: kernel/rcu/srcutree.c:644
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff81132680-ffffffff81132900: srcu_funnel_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void srcu_funnel_gp_start(struct srcu_struct *ssp, struct srcu_data *sdp, long unsigned int s, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112de70)
Location: kernel/rcu/srcutree.c:633
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8112de70-ffffffff8112e0f0: srcu_funnel_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void srcu_funnel_gp_start(struct srcu_struct *ssp, struct srcu_data *sdp, long unsigned int s, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e3c0)
Location: kernel/rcu/srcutree.c:636
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff8112e3c0-ffffffff8112e636: srcu_funnel_gp_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void srcu_funnel_gp_start(struct srcu_struct *ssp, struct srcu_data *sdp, long unsigned int s, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:628
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff8114f890-ffffffff8114fb1a: srcu_funnel_gp_start (STB_LOCAL)
ffffffff81cae2ae-ffffffff81cae2c2: srcu_funnel_gp_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void srcu_funnel_gp_start(struct srcu_struct *ssp, struct srcu_data *sdp, long unsigned int s, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:882
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff81176ae0-ffffffff81176e04: srcu_funnel_gp_start (STB_LOCAL)
ffffffff81e5e8fb-ffffffff81e5e90f: srcu_funnel_gp_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void srcu_funnel_gp_start(struct srcu_struct *ssp, struct srcu_data *sdp, long unsigned int s, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:946
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff811aced0-ffffffff811ad1f4: srcu_funnel_gp_start (STB_LOCAL)
ffffffff82059eb1-ffffffff82059ec5: srcu_funnel_gp_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void srcu_funnel_gp_start(struct srcu_struct *ssp, struct srcu_data *sdp, long unsigned int s, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:998
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff811bee20-ffffffff811bf14f: srcu_funnel_gp_start (STB_LOCAL)
ffffffff820d86a8-ffffffff820d86bc: srcu_funnel_gp_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void srcu_funnel_gp_start(struct srcu_struct *ssp, struct srcu_data *sdp, long unsigned int s, bool do_norm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/srcutree.c (0)
Location: kernel/rcu/srcutree.c:989
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff811cf290-ffffffff811cf5bf: srcu_funnel_gp_start (STB_LOCAL)
ffffffff821b3972-ffffffff821b3986: srcu_funnel_gp_start.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff80001018b388)
Location: kernel/rcu/srcutree.c:631
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d91a0)
Location: kernel/rcu/srcutree.c:631
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e4e28)
Location: kernel/rcu/srcutree.c:631
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011f764)
Location: kernel/rcu/srcutree.c:631
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111d3eb)
Location: kernel/rcu/srcutree.c:631
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110e4a1)
Location: kernel/rcu/srcutree.c:631
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111b2db)
Location: kernel/rcu/srcutree.c:631
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811272ab)
Location: kernel/rcu/srcutree.c:631
Inline: True
Inline callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
