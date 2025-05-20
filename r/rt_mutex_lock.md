# Function: <code>rt_mutex_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81822cf0)
Location: kernel/locking/rtmutex.c:1397
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_lock_adapter
```
**Symbols:**

```
ffffffff81822cf0-ffffffff81822d2f: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8189d240)
Location: kernel/locking/rtmutex.c:1406
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffffffff8189d240-ffffffff8189d27f: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff818d2140)
Location: kernel/locking/rtmutex.c:1470
Inline: False
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffffffff818d2140-ffffffff818d217f: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81909300)
Location: kernel/locking/rtmutex.c:1479
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffffffff81909300-ffffffff8190933f: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81993420)
Location: kernel/locking/rtmutex.c:1474
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffffffff81993420-ffffffff8199345f: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff819ef9f0)
Location: kernel/locking/rtmutex.c:1496
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffffffff819ef9f0-ffffffff819efa2e: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2ad40)
Location: kernel/locking/rtmutex.c:1496
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffffffff81a2ad40-ffffffff81a2ad7e: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a9ba30)
Location: kernel/locking/rtmutex.c:1497
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffffffff81a9ba30-ffffffff81a9ba73: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ad3380)
Location: kernel/locking/rtmutex.c:1495
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffffffff81ad3380-ffffffff81ad33c3: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81bcb470)
Location: kernel/locking/rtmutex.c:1493
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffffffff81bcb470-ffffffff81bcb4b7: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c44310)
Location: kernel/locking/rtmutex.c:1493
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffffffff81c44310-ffffffff81c44357: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c37280)
Location: kernel/locking/rtmutex.c:1416
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffffffff81c37280-ffffffff81c372c3: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d55b90)
Location: kernel/locking/rtmutex_api.c:62
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffffffff81d55b90-ffffffff81d55bd0: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f27860)
Location: kernel/locking/rtmutex_api.c:69
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_adapter_dw_psp_lock_bus
```
**Symbols:**

```
ffffffff81f27860-ffffffff81f27917: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d3340)
Location: kernel/locking/rtmutex_api.c:69
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
  - drivers/i2c/busses/i2c-designware-amdpsp.c:i2c_adapter_dw_psp_lock_bus
```
**Symbols:**

```
ffffffff820d3340-ffffffff820d33f7: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82157690)
Location: kernel/locking/rtmutex_api.c:69
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffffffff82157690-ffffffff821576fc: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff8223a4d0)
Location: kernel/locking/rtmutex_api.c:69
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffffffff8223a4d0-ffffffff8223a546: rt_mutex_lock (STB_GLOBAL)
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
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff800010da5d68)
Location: kernel/locking/rtmutex.c:1495
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffff800010da5d68-ffff800010da5de4: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0e9dba4)
Location: kernel/locking/rtmutex.c:1495
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
c0e9dba4-c0e9dc10: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c000000000ee8410)
Location: kernel/locking/rtmutex.c:1495
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
c000000000ee8410-c000000000ee84a4: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe0008c8394)
Location: kernel/locking/rtmutex.c:1495
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffffffe0008c8394-ffffffe0008c83ec: rt_mutex_lock (STB_GLOBAL)
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
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a721f0)
Location: kernel/locking/rtmutex.c:1495
Inline: False
```
**Symbols:**

```
ffffffff81a721f0-ffffffff81a72233: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81a2e5c0)
Location: kernel/locking/rtmutex.c:1495
Inline: False
```
**Symbols:**

```
ffffffff81a2e5c0-ffffffff81a2e603: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81ade600)
Location: kernel/locking/rtmutex.c:1495
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffffffff81ade600-ffffffff81ade643: rt_mutex_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rt_mutex_lock(struct rt_mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81aeaab0)
Location: kernel/locking/rtmutex.c:1495
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_adapter_lock_bus
```
**Symbols:**

```
ffffffff81aeaab0-ffffffff81aeaae0: rt_mutex_lock (STB_GLOBAL)
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
