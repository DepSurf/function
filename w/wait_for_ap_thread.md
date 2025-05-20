# Function: <code>wait_for_ap_thread</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108ba8f)
Location: kernel/cpu.c:242
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:__cpuhp_kick_ap
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
In kernel/cpu.c (ffffffff8108f357)
Location: kernel/cpu.c:239
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:__cpuhp_kick_ap
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
In kernel/cpu.c (ffffffff81097657)
Location: kernel/cpu.c:237
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:__cpuhp_kick_ap
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
In kernel/cpu.c (ffffffff8109bbc7)
Location: kernel/cpu.c:238
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:__cpuhp_kick_ap
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
In kernel/cpu.c (ffffffff810a2147)
Location: kernel/cpu.c:241
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:__cpuhp_kick_ap
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
In kernel/cpu.c (ffffffff81bc0b91)
Location: kernel/cpu.c:242
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:cpuhp_invoke_ap_callback
  - kernel/cpu.c:cpuhp_invoke_ap_callback
  - kernel/cpu.c:bringup_wait_for_ap
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
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
In kernel/cpu.c (ffffffff81c39c21)
Location: kernel/cpu.c:242
Inline: True
Inline callers:
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:cpuhp_invoke_ap_callback
  - kernel/cpu.c:cpuhp_invoke_ap_callback
  - kernel/cpu.c:bringup_wait_for_ap
  - kernel/cpu.c:cpuhp_kick_ap
  - kernel/cpu.c:cpuhp_kick_ap
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
In kernel/cpu.c (ffffffff810a6836)
Location: kernel/cpu.c:247
Inline: True
Inline callers:
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:cpuhp_issue_call
  - kernel/cpu.c:_cpu_down
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:cpuhp_kick_ap_work
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:bringup_cpu
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
In kernel/cpu.c (ffffffff810b767f)
Location: kernel/cpu.c:258
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:__cpuhp_kick_ap
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
In kernel/cpu.c (ffffffff810cdffe)
Location: kernel/cpu.c:259
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:__cpuhp_kick_ap
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
In kernel/cpu.c (ffffffff810ec16e)
Location: kernel/cpu.c:259
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:__cpuhp_kick_ap
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
In kernel/cpu.c (ffffffff810f9696)
Location: kernel/cpu.c:262
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:cpuhp_bringup_ap
  - kernel/cpu.c:__cpuhp_kick_ap
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
In kernel/cpu.c (ffffffff81102aa6)
Location: kernel/cpu.c:262
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:cpuhp_bringup_ap
  - kernel/cpu.c:__cpuhp_kick_ap
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
In kernel/cpu.c (ffff8000100f70d0)
Location: kernel/cpu.c:241
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:__cpuhp_kick_ap
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
In kernel/cpu.c (c0355598)
Location: kernel/cpu.c:241
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:__cpuhp_kick_ap
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
In kernel/cpu.c (c00000000013d634)
Location: kernel/cpu.c:241
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:__cpuhp_kick_ap
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
In kernel/cpu.c (ffffffe0000c2e62)
Location: kernel/cpu.c:241
Inline: True
Inline callers:
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:__cpuhp_kick_ap
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
In kernel/cpu.c (ffffffff8109ba67)
Location: kernel/cpu.c:241
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:__cpuhp_kick_ap
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
In kernel/cpu.c (ffffffff8108a497)
Location: kernel/cpu.c:241
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:__cpuhp_kick_ap
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
In kernel/cpu.c (ffffffff8109ba17)
Location: kernel/cpu.c:241
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:__cpuhp_kick_ap
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
In kernel/cpu.c (ffffffff810a3687)
Location: kernel/cpu.c:241
Inline: True
Inline callers:
  - kernel/cpu.c:takedown_cpu
  - kernel/cpu.c:bringup_cpu
  - kernel/cpu.c:__cpuhp_kick_ap
```
</details>
</li>
</ul>

## Differences
