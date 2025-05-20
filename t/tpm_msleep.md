# Function: <code>tpm_msleep</code>

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
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8161e1c1)
Location: drivers/char/tpm/tpm.h:523
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:wait_for_tpm_stat
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/char/tpm/tpm2-cmd.c (ffffffff8161ff38)
Location: drivers/char/tpm/tpm.h:523
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-cmd.c:tpm2_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81624c88)
Location: drivers/char/tpm/tpm.h:523
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:get_burstcount
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81657ed1)
Location: drivers/char/tpm/tpm.h:543
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_pm_suspend
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_do_selftest
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8165ef88)
Location: drivers/char/tpm/tpm.h:543
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8167675d)
Location: drivers/char/tpm/tpm.h:527
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81677959)
Location: drivers/char/tpm/tpm.h:527
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167d444)
Location: drivers/char/tpm/tpm.h:527
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816ac442)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816ad5d4)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816b3ee8)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816cf1a2)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816d02b4)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816d6bc8)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81784162)
Location: drivers/char/tpm/tpm.h:188
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff817851af)
Location: drivers/char/tpm/tpm.h:188
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8178aef8)
Location: drivers/char/tpm/tpm.h:188
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8179b6b2)
Location: drivers/char/tpm/tpm.h:186
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8179c5ef)
Location: drivers/char/tpm/tpm.h:186
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff817a1d38)
Location: drivers/char/tpm/tpm.h:186
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff8177e1f0)
Location: drivers/char/tpm/tpm.h:186
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8177f11f)
Location: drivers/char/tpm/tpm.h:186
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81784a38)
Location: drivers/char/tpm/tpm.h:186
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff818043e0)
Location: drivers/char/tpm/tpm.h:186
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff8180543f)
Location: drivers/char/tpm/tpm.h:186
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8180b518)
Location: drivers/char/tpm/tpm.h:186
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81943d63)
Location: drivers/char/tpm/tpm.h:186
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81944ebf)
Location: drivers/char/tpm/tpm.h:186
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8194b968)
Location: drivers/char/tpm/tpm.h:186
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81aa6988)
Location: drivers/char/tpm/tpm.h:260
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81aa7e5f)
Location: drivers/char/tpm/tpm.h:260
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81aaf4e1)
Location: drivers/char/tpm/tpm.h:260
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81af21d3)
Location: drivers/char/tpm/tpm.h:261
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81af368f)
Location: drivers/char/tpm/tpm.h:261
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81afb3b6)
Location: drivers/char/tpm/tpm.h:261
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81b45763)
Location: drivers/char/tpm/tpm.h:261
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_try_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81b46c1f)
Location: drivers/char/tpm/tpm.h:261
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff81b4ea46)
Location: drivers/char/tpm/tpm.h:261
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:__tpm_tis_request_locality
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffff8000108b97c4)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffff8000108bab40)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffff8000108c18a8)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c09b2bf8)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (c09b3f78)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (c09ba648)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (c00000000095a73c)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (c00000000095bfc0)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (c00000000096450c)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffe000569bd0)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffe00056b564)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffe000573146)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff81694bf2)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff81695d04)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8169c618)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816725e2)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816736f4)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff8167a008)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816c2e62)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816c3f74)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816ca888)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm-interface.c (ffffffff816dd432)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
  - drivers/char/tpm/tpm-interface.c:tpm_transmit
```
```
In drivers/char/tpm/tpm1-cmd.c (ffffffff816de519)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm1-cmd.c:tpm1_pm_suspend
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
  - drivers/char/tpm/tpm1-cmd.c:tpm1_do_selftest
```
```
In drivers/char/tpm/tpm_tis_core.c (ffffffff816e4d58)
Location: drivers/char/tpm/tpm.h:402
Inline: True
Inline callers:
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_core_init
  - drivers/char/tpm/tpm_tis_core.c:tpm_tis_send
  - drivers/char/tpm/tpm_tis_core.c:request_locality
  - drivers/char/tpm/tpm_tis_core.c:release_locality
```
</details>
</li>
</ul>

## Differences
