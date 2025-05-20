# Function: <code>xs_net</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_state.c (0)
Location: include/net/xfrm.h:235
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff817b2896)
Location: include/net/xfrm.h:235
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_state.c (ffffffff817b73d3)
Location: include/net/xfrm.h:235
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:xfrm_state_add
```
```
In net/xfrm/xfrm_output.c (ffffffff817bc16c)
Location: include/net/xfrm.h:235
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff817bc8c4)
Location: include/net/xfrm.h:235
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_state.c (0)
Location: include/net/xfrm.h:231
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff8181f983)
Location: include/net/xfrm.h:231
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_state.c (ffffffff81824405)
Location: include/net/xfrm.h:231
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
  - net/xfrm/xfrm_state.c:__xfrm_state_destroy
```
```
In net/xfrm/xfrm_output.c (ffffffff818290a3)
Location: include/net/xfrm.h:231
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff818299b7)
Location: include/net/xfrm.h:231
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_state.c (0)
Location: include/net/xfrm.h:231
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff818511e3)
Location: include/net/xfrm.h:231
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_state.c (ffffffff81855d55)
Location: include/net/xfrm.h:231
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff8185aa83)
Location: include/net/xfrm.h:231
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff8185b387)
Location: include/net/xfrm.h:231
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_state.c (0)
Location: include/net/xfrm.h:245
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff81875e2f)
Location: include/net/xfrm.h:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_state.c (ffffffff818799c5)
Location: include/net/xfrm.h:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff8187e9fc)
Location: include/net/xfrm.h:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff8187f228)
Location: include/net/xfrm.h:245
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/net/xfrm.h:245
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/xfrm4_state.c (0)
Location: include/net/xfrm.h:249
Inline: True
```
```
In net/xfrm/xfrm_policy.c (ffffffff818f6f42)
Location: include/net/xfrm.h:249
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_state.c (ffffffff818fa418)
Location: include/net/xfrm.h:249
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff818ffa6c)
Location: include/net/xfrm.h:249
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff81900348)
Location: include/net/xfrm.h:249
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
```
In net/xfrm/xfrm_device.c (0)
Location: include/net/xfrm.h:249
Inline: True
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
In net/ipv4/xfrm4_state.c (ffffffff819490c5)
Location: include/net/xfrm.h:249
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_init_flags
```
```
In net/xfrm/xfrm_policy.c (ffffffff8194cf9a)
Location: include/net/xfrm.h:249
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_resolve_and_create_bundle
```
```
In net/xfrm/xfrm_state.c (ffffffff819520e8)
Location: include/net/xfrm.h:249
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff819564e4)
Location: include/net/xfrm.h:249
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff81956e35)
Location: include/net/xfrm.h:249
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
```
In net/xfrm/xfrm_device.c (ffffffff81957ece)
Location: include/net/xfrm.h:249
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/ipv4/xfrm4_state.c (ffffffff8197ad75)
Location: include/net/xfrm.h:251
Inline: True
Inline callers:
  - net/ipv4/xfrm4_state.c:xfrm4_init_flags
```
```
In net/xfrm/xfrm_policy.c (ffffffff8197e887)
Location: include/net/xfrm.h:251
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_state.c (ffffffff81985388)
Location: include/net/xfrm.h:251
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff8198b166)
Location: include/net/xfrm.h:251
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff8198ba55)
Location: include/net/xfrm.h:251
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
```
In net/xfrm/xfrm_device.c (ffffffff8198cf76)
Location: include/net/xfrm.h:251
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (ffffffff819e788f)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_state.c (ffffffff819ee784)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff819f6696)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff819f6fa5)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
```
In net/xfrm/xfrm_device.c (ffffffff819f87cd)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (ffffffff81a1e87f)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_state.c (ffffffff81a25664)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff81a2d316)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a2dbf5)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
```
In net/xfrm/xfrm_device.c (ffffffff81a2f42d)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (ffffffff81b113e6)
Location: include/net/xfrm.h:263
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_state.c (ffffffff81b18da8)
Location: include/net/xfrm.h:263
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2000e)
Location: include/net/xfrm.h:263
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b20f91)
Location: include/net/xfrm.h:263
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
```
In net/xfrm/xfrm_device.c (ffffffff81b2205c)
Location: include/net/xfrm.h:263
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (ffffffff81b1fc7f)
Location: include/net/xfrm.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_state.c (ffffffff81b2723b)
Location: include/net/xfrm.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e920)
Location: include/net/xfrm.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b2f961)
Location: include/net/xfrm.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
```
In net/xfrm/xfrm_device.c (ffffffff81b30abb)
Location: include/net/xfrm.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (ffffffff81b0db61)
Location: include/net/xfrm.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_state.c (ffffffff81b14e5b)
Location: include/net/xfrm.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1c6a3)
Location: include/net/xfrm.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81b1d677)
Location: include/net/xfrm.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
```
In net/xfrm/xfrm_device.c (ffffffff81b1e7f0)
Location: include/net/xfrm.h:265
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (ffffffff81bd072b)
Location: include/net/xfrm.h:276
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_state.c (ffffffff81bd8fd1)
Location: include/net/xfrm.h:276
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff81be1013)
Location: include/net/xfrm.h:276
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81be24e1)
Location: include/net/xfrm.h:276
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
```
In net/xfrm/xfrm_device.c (ffffffff81be330e)
Location: include/net/xfrm.h:276
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (ffffffff81d66bde)
Location: include/net/xfrm.h:281
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_state.c (ffffffff81d6fd56)
Location: include/net/xfrm.h:281
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77ec3)
Location: include/net/xfrm.h:281
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81d795d7)
Location: include/net/xfrm.h:281
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
```
In net/xfrm/xfrm_device.c (ffffffff81d7a4b1)
Location: include/net/xfrm.h:281
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (ffffffff81f2f920)
Location: include/net/xfrm.h:289
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81f3b56a)
Location: include/net/xfrm.h:289
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff81f44763)
Location: include/net/xfrm.h:289
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81f46067)
Location: include/net/xfrm.h:289
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
```
In net/xfrm/xfrm_device.c (ffffffff81f47407)
Location: include/net/xfrm.h:289
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (ffffffff81f903b0)
Location: include/net/xfrm.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff81f9af8d)
Location: include/net/xfrm.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3f64)
Location: include/net/xfrm.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff81fa5779)
Location: include/net/xfrm.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
```
In net/xfrm/xfrm_device.c (ffffffff81fa6e5a)
Location: include/net/xfrm.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (ffffffff8205e110)
Location: include/net/xfrm.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_dst_lookup
```
```
In net/xfrm/xfrm_state.c (ffffffff820682ed)
Location: include/net/xfrm.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff82071294)
Location: include/net/xfrm.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffff82072ac9)
Location: include/net/xfrm.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
```
In net/xfrm/xfrm_device.c (ffffffff82074139)
Location: include/net/xfrm.h:294
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (ffff800010cdaca0)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_state.c (ffff800010ce2b18)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffff800010cec3e8)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffff800010cecaac)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
```
In net/xfrm/xfrm_device.c (ffff800010cee618)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (c0de4b00)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_state.c (c0dec1ac)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (c0df42c4)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (c0df4920)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
```
In net/xfrm/xfrm_device.c (c0df6444)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (c000000000dffc14)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_state.c (c000000000e05d40)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (c000000000e10520)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (c000000000e10cd8)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
```
In net/xfrm/xfrm_device.c (c000000000e132b8)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (ffffffe00082c830)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_state.c (ffffffe000831414)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffe000839b72)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_one
```
```
In net/xfrm/xfrm_replay.c (ffffffe00083a0c4)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance
```
```
In net/xfrm/xfrm_device.c (ffffffe00083b76e)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (ffffffff819bdf0f)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_state.c (ffffffff819c4cf4)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff819cc9a6)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff819cd285)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
```
In net/xfrm/xfrm_device.c (ffffffff819ceabd)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (ffffffff8197acff)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_state.c (ffffffff81981ae4)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff81989796)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff8198a075)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
```
In net/xfrm/xfrm_device.c (ffffffff8198b884)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (ffffffff81a2898f)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_state.c (ffffffff81a2f774)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff81a37426)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a37d05)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
```
In net/xfrm/xfrm_device.c (ffffffff81a3953d)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
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
In net/xfrm/xfrm_policy.c (ffffffff81a33f84)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_create
```
```
In net/xfrm/xfrm_state.c (ffffffff81a3b0d9)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:xfrm_replay_timer_handler
  - net/xfrm/xfrm_state.c:xfrm_alloc_spi
  - net/xfrm/xfrm_state.c:xfrm_state_update
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_add
  - net/xfrm/xfrm_state.c:xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_bump_genids
  - net/xfrm/xfrm_state.c:__xfrm_state_insert
  - net/xfrm/xfrm_state.c:__xfrm_state_delete
```
```
In net/xfrm/xfrm_output.c (ffffffff81a42db6)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_output_resume
  - net/xfrm/xfrm_output.c:xfrm_output_resume
```
```
In net/xfrm/xfrm_replay.c (ffffffff81a44325)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_replay.c:xfrm_replay_overflow_offload
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_esn
  - net/xfrm/xfrm_replay.c:xfrm_replay_advance_bmp
```
```
In net/xfrm/xfrm_device.c (ffffffff81a44f6d)
Location: include/net/xfrm.h:262
Inline: True
Inline callers:
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
  - net/xfrm/xfrm_device.c:validate_xmit_xfrm
```
</details>
</li>
</ul>

## Differences
