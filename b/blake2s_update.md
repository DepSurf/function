# Function: <code>blake2s_update</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blake2s_update(struct blake2s_state *state, const u8 *in, size_t inlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/blake2s.c (ffffffff816f02c0)
Location: lib/crypto/blake2s.c:24
Inline: False
Direct callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:mix_interrupt_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
  - drivers/char/random.c:random_init
  - drivers/char/random.c:random_init
  - drivers/char/random.c:random_init
```
**Symbols:**

```
ffffffff816f02c0-ffffffff816f0391: blake2s_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blake2s_update(struct blake2s_state *state, const u8 *in, size_t inlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/crypto/blake2s.c (ffffffff817e1db0)
Location: lib/crypto/blake2s.c:24
Inline: False
Direct callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:mix_interrupt_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
  - drivers/char/random.c:random_init
  - drivers/char/random.c:random_init_early
  - drivers/char/random.c:random_init_early
  - drivers/char/random.c:random_init_early
  - drivers/char/random.c:add_bootloader_randomness
```
**Symbols:**

```
ffffffff817e1db0-ffffffff817e1e81: blake2s_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void blake2s_update(struct blake2s_state *state, const u8 *in, size_t inlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/crypto/blake2s.c (0)
Location: lib/crypto/blake2s.c:24
Inline: False
Direct callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:mix_interrupt_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
  - drivers/char/random.c:random_init
  - drivers/char/random.c:random_init_early
  - drivers/char/random.c:random_init_early
  - drivers/char/random.c:random_init_early
  - drivers/char/random.c:add_bootloader_randomness
```
**Symbols:**

```
ffffffff820f90f9-ffffffff820f9139: blake2s_update.cold (STB_LOCAL)
ffffffff81821c50-ffffffff81821de6: blake2s_update (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void blake2s_update(struct blake2s_state *state, const u8 *in, size_t inlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/crypto/blake2s.c (0)
Location: lib/crypto/blake2s.c:24
Inline: False
Direct callers:
  - drivers/char/random.c:write_pool_user
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:try_to_generate_entropy
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:add_timer_randomness
  - drivers/char/random.c:mix_interrupt_randomness
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:add_device_randomness
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_pm_notification
  - drivers/char/random.c:random_init
  - drivers/char/random.c:random_init
  - drivers/char/random.c:random_init_early
  - drivers/char/random.c:random_init_early
  - drivers/char/random.c:random_init_early
  - drivers/char/random.c:add_bootloader_randomness
```
**Symbols:**

```
ffffffff821d6cd5-ffffffff821d6d15: blake2s_update.cold (STB_LOCAL)
ffffffff81867c90-ffffffff81867e26: blake2s_update (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
