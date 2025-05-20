# Function: <code>rcu_momentary_dyntick_idle</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e6500)
Location: kernel/rcu/tree.c:304
Inline: False
Direct callers:
  - kernel/rcu/tree.c:force_qs_rnp
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_gp_kthread
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/rcu/tree.c:rcu_check_callbacks
```
**Symbols:**

```
ffffffff810e6500-ffffffff810e65ab: rcu_momentary_dyntick_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eac90)
Location: kernel/rcu/tree.c:299
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_all_qs
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffff810eac90-ffffffff810ead20: rcu_momentary_dyntick_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2060)
Location: kernel/rcu/tree.c:300
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_all_qs
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffff810f2060-ffffffff810f20f0: rcu_momentary_dyntick_idle (STB_LOCAL)
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
In kernel/rcu/tree.c (ffffffff810f47d1)
Location: kernel/rcu/tree.c:445
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
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
In kernel/rcu/tree.c (ffffffff810fe6a7)
Location: kernel/rcu/tree.c:442
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
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
In kernel/rcu/tree.c (ffffffff81105797)
Location: kernel/rcu/tree.c:429
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81110130)
Location: kernel/rcu/tree.c:371
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffff81110130-ffffffff81110168: rcu_momentary_dyntick_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81119ac0)
Location: kernel/rcu/tree.c:366
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffff81119ac0-ffffffff81119af8: rcu_momentary_dyntick_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81125e50)
Location: kernel/rcu/tree.c:367
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffff81125e50-ffffffff81125e88: rcu_momentary_dyntick_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81133740)
Location: kernel/rcu/tree.c:407
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:multi_cpu_stop
```
**Symbols:**

```
ffffffff81133740-ffffffff81133778: rcu_momentary_dyntick_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112edf0)
Location: kernel/rcu/tree.c:420
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:multi_cpu_stop
```
**Symbols:**

```
ffffffff8112edf0-ffffffff8112ee1d: rcu_momentary_dyntick_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112f450)
Location: kernel/rcu/tree.c:426
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:multi_cpu_stop
```
**Symbols:**

```
ffffffff8112f450-ffffffff8112f47d: rcu_momentary_dyntick_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81152eab)
Location: kernel/rcu/tree.c:402
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
Direct callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:multi_cpu_stop
```
**Symbols:**

```
ffffffff81150a00-ffffffff81150a20: rcu_momentary_dyntick_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8117c890)
Location: kernel/rcu/tree.c:413
Inline: False
Direct callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:multi_cpu_stop
```
**Symbols:**

```
ffffffff8117c890-ffffffff8117c8ee: rcu_momentary_dyntick_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811b6c20)
Location: kernel/rcu/tree.c:344
Inline: False
Direct callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:multi_cpu_stop
```
**Symbols:**

```
ffffffff811b6c20-ffffffff811b6c9a: rcu_momentary_dyntick_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811c7650)
Location: kernel/rcu/tree.c:325
Inline: False
Direct callers:
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:multi_cpu_stop
```
**Symbols:**

```
ffffffff811c7650-ffffffff811c76ca: rcu_momentary_dyntick_idle (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811d7b70)
Location: kernel/rcu/tree.c:326
Inline: False
Direct callers:
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/stop_machine.c:multi_cpu_stop
  - kernel/stop_machine.c:multi_cpu_stop
```
**Symbols:**

```
ffffffff811d7b70-ffffffff811d7bea: rcu_momentary_dyntick_idle (STB_GLOBAL)
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
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018c980)
Location: kernel/rcu/tree.c:367
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffff80001018c980-ffff80001018c9ec: rcu_momentary_dyntick_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dc040)
Location: kernel/rcu/tree.c:367
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
c03dc040-c03dc0d8: rcu_momentary_dyntick_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e6b00)
Location: kernel/rcu/tree.c:367
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
c0000000001e6b00-c0000000001e6b64: rcu_momentary_dyntick_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000120ff2)
Location: kernel/rcu/tree.c:367
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffe000120ff2-ffffffe000121058: rcu_momentary_dyntick_idle (STB_LOCAL)
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
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111e430)
Location: kernel/rcu/tree.c:367
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffff8111e430-ffffffff8111e468: rcu_momentary_dyntick_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8110f4e0)
Location: kernel/rcu/tree.c:367
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nocb_cb_kthread
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffff8110f4e0-ffffffff8110f518: rcu_momentary_dyntick_idle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_momentary_dyntick_idle();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111c320)
Location: kernel/rcu/tree.c:367
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_note_context_switch
```
**Symbols:**

```
ffffffff8111c320-ffffffff8111c358: rcu_momentary_dyntick_idle (STB_LOCAL)
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
