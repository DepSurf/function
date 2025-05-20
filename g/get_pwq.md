# Function: <code>get_pwq</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff81097a30)
Location: kernel/workqueue.c:1040
Inline: True
Direct callers:
  - kernel/workqueue.c:insert_work
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:wq_update_unbound_numa
```
**Symbols:**

```
ffffffff81097a30-ffffffff81097a70: get_pwq.isra.22 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff8109b110)
Location: kernel/workqueue.c:1059
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
```
**Symbols:**

```
ffffffff8109b110-ffffffff8109b150: get_pwq.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (ffffffff8109fef0)
Location: kernel/workqueue.c:1061
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
```
**Symbols:**

```
ffffffff8109fef0-ffffffff8109ff30: get_pwq.isra.20 (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff810a1262)
Location: kernel/workqueue.c:1061
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
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
In kernel/workqueue.c (ffffffff810a3dc0)
Location: kernel/workqueue.c:1063
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
```
**Symbols:**

```
ffffffff810a3dc0-ffffffff810a3dde: get_pwq.isra.19 (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff810aa8b0)
Location: kernel/workqueue.c:1061
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
```
**Symbols:**

```
ffffffff810aa8b0-ffffffff810aa8ce: get_pwq.isra.24 (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff810b3980)
Location: kernel/workqueue.c:1081
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
```
**Symbols:**

```
ffffffff810b3980-ffffffff810b399e: get_pwq.isra.24 (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff810b95e0)
Location: kernel/workqueue.c:1089
Inline: True
Direct callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
```
**Symbols:**

```
ffffffff810b95e0-ffffffff810b95ff: get_pwq.isra.0 (STB_LOCAL)
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
In kernel/workqueue.c (ffffffff810c3884)
Location: kernel/workqueue.c:1090
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810cb194)
Location: kernel/workqueue.c:1087
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810c62c4)
Location: kernel/workqueue.c:1087
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
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
In kernel/workqueue.c (ffffffff810c7bfc)
Location: kernel/workqueue.c:1088
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810da99e)
Location: kernel/workqueue.c:1114
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810f410f)
Location: kernel/workqueue.c:1110
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff811163cb)
Location: kernel/workqueue.c:1110
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:__queue_work
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112316b)
Location: kernel/workqueue.c:1308
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:__queue_work
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
In kernel/workqueue.c (ffffffff8112d15b)
Location: kernel/workqueue.c:1411
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_pod
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
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
In kernel/workqueue.c (ffff80001012159c)
Location: kernel/workqueue.c:1090
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void get_pwq(struct pool_workqueue *pwq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c036fd28)
Location: kernel/workqueue.c:1090
Inline: False
Direct callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
```
**Symbols:**

```
c036fd28-c036fd90: get_pwq (STB_LOCAL)
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
In kernel/workqueue.c (c00000000016abd4)
Location: kernel/workqueue.c:1090
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
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
In kernel/workqueue.c (ffffffe0000d9772)
Location: kernel/workqueue.c:1090
Inline: True
Inline callers:
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
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
In kernel/workqueue.c (ffffffff810bdbf4)
Location: kernel/workqueue.c:1090
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
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
In kernel/workqueue.c (ffffffff810ac424)
Location: kernel/workqueue.c:1090
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
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
In kernel/workqueue.c (ffffffff810bd154)
Location: kernel/workqueue.c:1090
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
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
In kernel/workqueue.c (ffffffff810c54d4)
Location: kernel/workqueue.c:1090
Inline: True
Inline callers:
  - kernel/workqueue.c:wq_update_unbound_numa
  - kernel/workqueue.c:rescuer_thread
  - kernel/workqueue.c:pool_mayday_timeout
  - kernel/workqueue.c:insert_work
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
