# Function: <code>show_workqueue_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109ca80)
Location: kernel/workqueue.c:4277
Inline: False
Direct callers:
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffff8109ca80-ffffffff8109cf00: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109fc70)
Location: kernel/workqueue.c:4375
Inline: False
Direct callers:
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffff8109fc70-ffffffff810a016d: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a4b40)
Location: kernel/workqueue.c:4405
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffff810a4b40-ffffffff810a503d: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a1ca0)
Location: kernel/workqueue.c:4425
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffff810a1ca0-ffffffff810a21b3: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a8520)
Location: kernel/workqueue.c:4452
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffff810a8520-ffffffff810a8a47: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4530
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffff810b02f8-ffffffff810b06cc: show_workqueue_state.cold.49 (STB_LOCAL)
ffffffff810aef70-ffffffff810af0b4: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4553
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffff810b9438-ffffffff810b980c: show_workqueue_state.cold.50 (STB_LOCAL)
ffffffff810b80e0-ffffffff810b8224: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4698
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffff810bf12b-ffffffff810bf502: show_workqueue_state.cold (STB_LOCAL)
ffffffff810bdc30-ffffffff810bdd4b: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4732
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffff810c558c-ffffffff810c5965: show_workqueue_state.cold (STB_LOCAL)
ffffffff810c4180-ffffffff810c429b: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4755
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffff810cd137-ffffffff810cd273: show_workqueue_state.cold (STB_LOCAL)
ffffffff810cbe00-ffffffff810cbf0d: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4768
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffff81bdbf98-ffffffff81bdc0d4: show_workqueue_state.cold (STB_LOCAL)
ffffffff810c6f30-ffffffff810c7042: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4775
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffff81bce0bd-ffffffff81bce1f9: show_workqueue_state.cold (STB_LOCAL)
ffffffff810c86d0-ffffffff810c87e2: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4814
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffff81ca5316-ffffffff81ca5417: show_workqueue_state.cold (STB_LOCAL)
ffffffff810db270-ffffffff810db3e6: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff800010121fa0)
Location: kernel/workqueue.c:4732
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffff800010121fa0-ffff800010122534: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c03759a8)
Location: kernel/workqueue.c:4732
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
c03759a8-c0375f18: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016b990)
Location: kernel/workqueue.c:4732
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
c00000000016b990-c00000000016bfd8: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000dab66)
Location: kernel/workqueue.c:4732
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffe0000dab66-ffffffe0000dafa8: show_workqueue_state (STB_GLOBAL)
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
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4732
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffff810bf8fc-ffffffff810bfcd5: show_workqueue_state.cold (STB_LOCAL)
ffffffff810be4f0-ffffffff810be60b: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4732
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffff810ae11c-ffffffff810ae4f5: show_workqueue_state.cold (STB_LOCAL)
ffffffff810acd20-ffffffff810ace3b: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4732
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffff810bee5c-ffffffff810bf235: show_workqueue_state.cold (STB_LOCAL)
ffffffff810bda50-ffffffff810bdb6b: show_workqueue_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void show_workqueue_state();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4732
Inline: False
Direct callers:
  - kernel/workqueue.c:destroy_workqueue
  - kernel/workqueue.c:destroy_workqueue
  - kernel/power/process.c:try_to_freeze_tasks
  - kernel/power/process.c:try_to_freeze_tasks
  - drivers/tty/sysrq.c:sysrq_handle_showstate
```
**Symbols:**

```
ffffffff810c71c7-ffffffff810c75a0: show_workqueue_state.cold (STB_LOCAL)
ffffffff810c5dd0-ffffffff810c5ef5: show_workqueue_state (STB_GLOBAL)
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
