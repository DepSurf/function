# Function: <code>rt_mutex_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81822d80)
Location: kernel/locking/rtmutex.c:1484
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:exit_pi_state_list
  - drivers/i2c/i2c-core.c:i2c_unlock_adapter
```
**Symbols:**

```
ffffffff81822d80-ffffffff81822e0b: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8189d2d0)
Location: kernel/locking/rtmutex.c:1493
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:exit_pi_state_list
  - drivers/i2c/i2c-core.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffffffff8189d2d0-ffffffff8189d35b: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff818d21d0)
Location: kernel/locking/rtmutex.c:1557
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:exit_pi_state_list
  - drivers/i2c/i2c-core.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffffffff818d21d0-ffffffff818d225b: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81908f00)
Location: kernel/locking/rtmutex.c:1582
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffffffff81908f00-ffffffff81908f77: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81993010)
Location: kernel/locking/rtmutex.c:1582
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffffffff81993010-ffffffff81993087: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff819ef5f0)
Location: kernel/locking/rtmutex.c:1602
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffffffff819ef5f0-ffffffff819ef667: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2a930)
Location: kernel/locking/rtmutex.c:1602
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffffffff81a2a930-ffffffff81a2a9a7: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a9b630)
Location: kernel/locking/rtmutex.c:1603
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffffffff81a9b630-ffffffff81a9b6a9: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ad2f80)
Location: kernel/locking/rtmutex.c:1601
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffffffff81ad2f80-ffffffff81ad2ff9: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81bcb030)
Location: kernel/locking/rtmutex.c:1599
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffffffff81bcb030-ffffffff81bcb0a7: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c43ec0)
Location: kernel/locking/rtmutex.c:1599
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffffffff81c43ec0-ffffffff81c43f37: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c35d80)
Location: kernel/locking/rtmutex.c:1477
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffffffff81c35d80-ffffffff81c35e75: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d54580)
Location: kernel/locking/rtmutex_api.c:116
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffffffff81d54580-ffffffff81d54682: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f260b0)
Location: kernel/locking/rtmutex_api.c:138
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_adapter_dw_psp_unlock_bus
```
**Symbols:**

```
ffffffff81f260b0-ffffffff81f261ce: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d1b70)
Location: kernel/locking/rtmutex_api.c:138
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_adapter_dw_psp_unlock_bus
```
**Symbols:**

```
ffffffff820d1b70-ffffffff820d1c8e: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82155ed0)
Location: kernel/locking/rtmutex_api.c:138
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffffffff82155ed0-ffffffff82155fee: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82238d10)
Location: kernel/locking/rtmutex_api.c:138
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffffffff82238d10-ffffffff82238e2e: rt_mutex_unlock (STB_GLOBAL)
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
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff800010da5800)
Location: kernel/locking/rtmutex.c:1601
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffff800010da5800-ffff800010da58c0: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0e9d68c)
Location: kernel/locking/rtmutex.c:1601
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
c0e9d68c-c0e9d758: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c000000000ee7e20)
Location: kernel/locking/rtmutex.c:1601
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
c000000000ee7e20-c000000000ee7ef8: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe0008c805c)
Location: kernel/locking/rtmutex.c:1601
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffffffe0008c805c-ffffffe0008c80c2: rt_mutex_unlock (STB_GLOBAL)
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
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a71df0)
Location: kernel/locking/rtmutex.c:1601
Inline: False
```
**Symbols:**

```
ffffffff81a71df0-ffffffff81a71e69: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2e1c0)
Location: kernel/locking/rtmutex.c:1601
Inline: False
```
**Symbols:**

```
ffffffff81a2e1c0-ffffffff81a2e239: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ade200)
Location: kernel/locking/rtmutex.c:1601
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffffffff81ade200-ffffffff81ade279: rt_mutex_unlock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rt_mutex_unlock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81aea6a0)
Location: kernel/locking/rtmutex.c:1601
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_unlock_bus
```
**Symbols:**

```
ffffffff81aea6a0-ffffffff81aea727: rt_mutex_unlock (STB_GLOBAL)
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
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
