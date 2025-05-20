# Function: <code>rt_mutex_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81822980)
Location: kernel/locking/rtmutex.c:1470
Inline: False
Direct callers:
  - kernel/futex.c:fixup_owner
  - kernel/futex.c:futex_lock_pi
  - drivers/i2c/i2c-core.c:i2c_trylock_adapter
```
**Symbols:**

```
ffffffff81822980-ffffffff81822a24: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8189cea0)
Location: kernel/locking/rtmutex.c:1479
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:fixup_owner
  - drivers/i2c/i2c-core.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffffffff8189cea0-ffffffff8189cf6a: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff818d1d70)
Location: kernel/locking/rtmutex.c:1543
Inline: False
Direct callers:
  - kernel/futex.c:futex_lock_pi
  - kernel/futex.c:fixup_owner
  - drivers/i2c/i2c-core.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffffffff818d1d70-ffffffff818d1e48: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81908f80)
Location: kernel/locking/rtmutex.c:1562
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffffffff81908f80-ffffffff8190902a: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81993090)
Location: kernel/locking/rtmutex.c:1562
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffffffff81993090-ffffffff8199313b: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff819ef670)
Location: kernel/locking/rtmutex.c:1582
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffffffff819ef670-ffffffff819ef71b: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2a9b0)
Location: kernel/locking/rtmutex.c:1582
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffffffff81a2a9b0-ffffffff81a2aa6e: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a9b6b0)
Location: kernel/locking/rtmutex.c:1583
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffffffff81a9b6b0-ffffffff81a9b76d: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ad3000)
Location: kernel/locking/rtmutex.c:1581
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffffffff81ad3000-ffffffff81ad30bd: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81bcb190)
Location: kernel/locking/rtmutex.c:1579
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffffffff81bcb190-ffffffff81bcb256: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c44030)
Location: kernel/locking/rtmutex.c:1579
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffffffff81c44030-ffffffff81c440f6: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c36160)
Location: kernel/locking/rtmutex.c:1450
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffffffff81c36160-ffffffff81c361f1: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d54a50)
Location: kernel/locking/rtmutex_api.c:96
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffffffff81d54a50-ffffffff81d54ada: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f265f0)
Location: kernel/locking/rtmutex_api.c:118
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_adapter_dw_psp_trylock_bus
```
**Symbols:**

```
ffffffff81f265f0-ffffffff81f26681: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d2090)
Location: kernel/locking/rtmutex_api.c:118
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_adapter_dw_psp_trylock_bus
```
**Symbols:**

```
ffffffff820d2090-ffffffff820d2121: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff821562b0)
Location: kernel/locking/rtmutex_api.c:118
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffffffff821562b0-ffffffff82156341: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff822390f0)
Location: kernel/locking/rtmutex_api.c:118
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffffffff822390f0-ffffffff82239181: rt_mutex_trylock (STB_GLOBAL)
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
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff800010da5a28)
Location: kernel/locking/rtmutex.c:1581
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffff800010da5a28-ffff800010da5b60: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0e9d888)
Location: kernel/locking/rtmutex.c:1581
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
c0e9d888-c0e9d9ac: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c000000000ee80b0)
Location: kernel/locking/rtmutex.c:1581
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
c000000000ee80b0-c000000000ee81f0: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe0008c80c2)
Location: kernel/locking/rtmutex.c:1581
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffffffe0008c80c2-ffffffe0008c817c: rt_mutex_trylock (STB_GLOBAL)
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
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a71e70)
Location: kernel/locking/rtmutex.c:1581
Inline: False
```
**Symbols:**

```
ffffffff81a71e70-ffffffff81a71f2d: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2e240)
Location: kernel/locking/rtmutex.c:1581
Inline: False
```
**Symbols:**

```
ffffffff81a2e240-ffffffff81a2e2fd: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ade280)
Location: kernel/locking/rtmutex.c:1581
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffffffff81ade280-ffffffff81ade33d: rt_mutex_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rt_mutex_trylock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81aea730)
Location: kernel/locking/rtmutex.c:1581
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_trylock_bus
```
**Symbols:**

```
ffffffff81aea730-ffffffff81aea7ed: rt_mutex_trylock (STB_GLOBAL)
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
