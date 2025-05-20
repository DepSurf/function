# Function: <code>put_pwq_unlocked</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void put_pwq_unlocked(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810994c0)
Location: kernel/workqueue.c:1078
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff810994c0-ffffffff810994f7: put_pwq_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void put_pwq_unlocked(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109ca40)
Location: kernel/workqueue.c:1097
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:apply_wqattrs_cleanup
```
**Symbols:**

```
ffffffff8109ca40-ffffffff8109ca77: put_pwq_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void put_pwq_unlocked(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a1ba0)
Location: kernel/workqueue.c:1099
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:apply_wqattrs_cleanup
```
**Symbols:**

```
ffffffff810a1ba0-ffffffff810a1bd7: put_pwq_unlocked (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810a2330)
Location: kernel/workqueue.c:1099
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff8109edd0-ffffffff8109ee01: put_pwq_unlocked.part.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810a8bc0)
Location: kernel/workqueue.c:1101
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff810a5610-ffffffff810a5641: put_pwq_unlocked.part.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810af252)
Location: kernel/workqueue.c:1099
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff810ac2b0-ffffffff810ac2e1: put_pwq_unlocked.part.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810b83c2)
Location: kernel/workqueue.c:1119
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff810b5190-ffffffff810b51c1: put_pwq_unlocked.part.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810bdeac)
Location: kernel/workqueue.c:1127
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff810bafa0-ffffffff810bafd1: put_pwq_unlocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c445e)
Location: kernel/workqueue.c:1128
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff810c1200-ffffffff810c1231: put_pwq_unlocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810cc0ca)
Location: kernel/workqueue.c:1125
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff810ca0e0-ffffffff810ca11c: put_pwq_unlocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c720a)
Location: kernel/workqueue.c:1125
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff810c5210-ffffffff810c524c: put_pwq_unlocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c898e)
Location: kernel/workqueue.c:1126
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:wq_update_unbound_numa
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810db5aa)
Location: kernel/workqueue.c:1152
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff810d9800-ffffffff810d985d: put_pwq_unlocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810f4d11)
Location: kernel/workqueue.c:1148
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff810f18f0-ffffffff810f1950: put_pwq_unlocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff81117159)
Location: kernel/workqueue.c:1148
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff81114f10-ffffffff81114f70: put_pwq_unlocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff81124104)
Location: kernel/workqueue.c:1346
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff81120ee0-ffffffff81120f40: put_pwq_unlocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112e7a6)
Location: kernel/workqueue.c:1443
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_pod
  - kernel/workqueue.c:wq_update_pod
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffff800010122768)
Location: kernel/workqueue.c:1128
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffff80001011f138-ffff80001011f1cc: put_pwq_unlocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (c03760b4)
Location: kernel/workqueue.c:1128
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:apply_wqattrs_cleanup
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:apply_wqattrs_cleanup
```
**Symbols:**

```
c037249c-c03724e8: put_pwq_unlocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (c00000000016c280)
Location: kernel/workqueue.c:1128
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
c0000000001678f0-c0000000001679c4: put_pwq_unlocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffe0000db128)
Location: kernel/workqueue.c:1128
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:apply_wqattrs_cleanup
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:apply_wqattrs_cleanup
  - kernel/workqueue.c:apply_wqattrs_cleanup
```
**Symbols:**

```
ffffffe0000d8b5a-ffffffe0000d8be0: put_pwq_unlocked.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810be7ce)
Location: kernel/workqueue.c:1128
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff810bb570-ffffffff810bb5a1: put_pwq_unlocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810acff8)
Location: kernel/workqueue.c:1128
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff810aa040-ffffffff810aa06b: put_pwq_unlocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810bdd2e)
Location: kernel/workqueue.c:1128
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff810baad0-ffffffff810bab01: put_pwq_unlocked.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff810c60b5)
Location: kernel/workqueue.c:1128
Inline: True
Inline callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff810c3580-ffffffff810c35a8: put_pwq_unlocked.part.0 (STB_LOCAL)
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
</ul>
