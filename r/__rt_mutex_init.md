# Function: <code>__rt_mutex_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810cac00)
Location: kernel/locking/rtmutex.c:1534
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff810cac00-ffffffff810cac29: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d02f5)
Location: kernel/locking/rtmutex.c:1543
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff810cf6d0-ffffffff810cf6f9: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d6ce5)
Location: kernel/locking/rtmutex.c:1607
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
Direct callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
  - drivers/i2c/i2c-core.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff810d60b0-ffffffff810d60d9: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810d5cb5)
Location: kernel/locking/rtmutex.c:1655
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff810d5000-ffffffff810d5029: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ddc75)
Location: kernel/locking/rtmutex.c:1655
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff810dcf60-ffffffff810dcf89: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810e62c5)
Location: kernel/locking/rtmutex.c:1676
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff810e55f0-ffffffff810e5619: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810f1845)
Location: kernel/locking/rtmutex.c:1676
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff810f0b80-ffffffff810f0ba9: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fa135)
Location: kernel/locking/rtmutex.c:1677
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff810f9260-ffffffff810f9289: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81105f25)
Location: kernel/locking/rtmutex.c:1675
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81105050-ffffffff81105079: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81110e95)
Location: kernel/locking/rtmutex.c:1673
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8110fe40-ffffffff8110fe69: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff8110e045)
Location: kernel/locking/rtmutex.c:1673
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8110cff0-ffffffff8110d019: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81c35c50)
Location: kernel/locking/rtmutex.c:1555
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81c35c50-ffffffff81c35c79: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81d54450)
Location: kernel/locking/rtmutex_api.c:191
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81d54450-ffffffff81d54479: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff81f25f70)
Location: kernel/locking/rtmutex_api.c:213
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81f25f70-ffffffff81f25f9f: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff820d1a10)
Location: kernel/locking/rtmutex_api.c:213
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff820d1a10-ffffffff820d1a3f: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82155d80)
Location: kernel/locking/rtmutex_api.c:213
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff82155d80-ffffffff82155daf: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex_api.c (ffffffff82238bc0)
Location: kernel/locking/rtmutex_api.c:213
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff82238bc0-ffffffff82238bef: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffff80001016c13c)
Location: kernel/locking/rtmutex.c:1675
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffff80001016aca8-ffff80001016acd8: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c03b7a38)
Location: kernel/locking/rtmutex.c:1675
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
c03b68a8-c03b68d4: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (c0000000001c3c88)
Location: kernel/locking/rtmutex.c:1675
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
c0000000001c2540-c0000000001c2560: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffe00010c336)
Location: kernel/locking/rtmutex.c:1675
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffe00010b356-ffffffe00010b386: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ff235)
Location: kernel/locking/rtmutex.c:1675
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
```
**Symbols:**

```
ffffffff810fe360-ffffffff810fe389: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810ef425)
Location: kernel/locking/rtmutex.c:1675
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
```
**Symbols:**

```
ffffffff810ee560-ffffffff810ee589: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff810fc3f5)
Location: kernel/locking/rtmutex.c:1675
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff810fb520-ffffffff810fb549: __rt_mutex_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __rt_mutex_init(struct rt_mutex *lock, const char *name, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/locking/rtmutex.c (ffffffff81107625)
Location: kernel/locking/rtmutex.c:1675
Inline: True
Inline callers:
  - kernel/locking/rtmutex.c:rt_mutex_init_proxy_locked
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff811066f0-ffffffff81106719: __rt_mutex_init (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lock_class_key *key</code>
</li>
</ul>
</details>
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
