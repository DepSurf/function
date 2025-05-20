# Function: <code>__hwspin_lock_request</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff818118f0)
Location: drivers/hwspinlock/hwspinlock_core.c:486
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff818118f0-ffffffff818119f0: __hwspin_lock_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8185b4a0)
Location: drivers/hwspinlock/hwspinlock_core.c:513
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff8185b4a0-ffffffff8185b5a3: __hwspin_lock_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff8187a9a0)
Location: drivers/hwspinlock/hwspinlock_core.c:624
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff8187a9a0-ffffffff8187aaa3: __hwspin_lock_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:646
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff818c0330-ffffffff818c03b2: __hwspin_lock_request (STB_LOCAL)
ffffffff818c0a3f-ffffffff818c0ab6: __hwspin_lock_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:646
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff818f2e30-ffffffff818f2eba: __hwspin_lock_request (STB_LOCAL)
ffffffff818f34b4-ffffffff818f3518: __hwspin_lock_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:646
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff819c85e0-ffffffff819c8672: __hwspin_lock_request (STB_LOCAL)
ffffffff819c8d9b-ffffffff819c8dff: __hwspin_lock_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:646
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff819c8330-ffffffff819c83c2: __hwspin_lock_request (STB_LOCAL)
ffffffff81c2db8f-ffffffff81c2dbf3: __hwspin_lock_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:646
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff819ad280-ffffffff819ad312: __hwspin_lock_request (STB_LOCAL)
ffffffff81c1fd3e-ffffffff81c1fda2: __hwspin_lock_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:646
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81a5b7d0-ffffffff81a5b862: __hwspin_lock_request (STB_LOCAL)
ffffffff81d316a0-ffffffff81d31704: __hwspin_lock_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:646
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81bcb990-ffffffff81bcba36: __hwspin_lock_request (STB_LOCAL)
ffffffff81efdb65-ffffffff81efdbc9: __hwspin_lock_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81d752e0)
Location: drivers/hwspinlock/hwspinlock_core.c:646
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81d752e0-ffffffff81d753da: __hwspin_lock_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81de3220)
Location: drivers/hwspinlock/hwspinlock_core.c:646
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81de3220-ffffffff81de331a: __hwspin_lock_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffff81e99310)
Location: drivers/hwspinlock/hwspinlock_core.c:651
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81e99310-ffffffff81e9940a: __hwspin_lock_request (STB_LOCAL)
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
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffff800010b7e8d8)
Location: drivers/hwspinlock/hwspinlock_core.c:646
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffff800010b7e8d8-ffff800010b7ea28: __hwspin_lock_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c0c62580)
Location: drivers/hwspinlock/hwspinlock_core.c:646
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
c0c62580-c0c626a8: __hwspin_lock_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (c000000000c5a410)
Location: drivers/hwspinlock/hwspinlock_core.c:646
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
c000000000c5a410-c000000000c5a574: __hwspin_lock_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (ffffffe00072c974)
Location: drivers/hwspinlock/hwspinlock_core.c:646
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffe00072c974-ffffffe00072ca70: __hwspin_lock_request (STB_LOCAL)
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
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:646
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81894160-ffffffff818941ea: __hwspin_lock_request (STB_LOCAL)
ffffffff818947e4-ffffffff81894848: __hwspin_lock_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:646
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff8184c880-ffffffff8184c90a: __hwspin_lock_request (STB_LOCAL)
ffffffff8184ccbe-ffffffff8184cd22: __hwspin_lock_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:646
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff818e7c60-ffffffff818e7cea: __hwspin_lock_request (STB_LOCAL)
ffffffff818e82e4-ffffffff818e8348: __hwspin_lock_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int __hwspin_lock_request(struct hwspinlock *hwlock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/hwspinlock/hwspinlock_core.c (0)
Location: drivers/hwspinlock/hwspinlock_core.c:646
Inline: False
Direct callers:
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request_specific
  - drivers/hwspinlock/hwspinlock_core.c:hwspin_lock_request
```
**Symbols:**

```
ffffffff81904980-ffffffff81904a0a: __hwspin_lock_request (STB_LOCAL)
ffffffff81904f4c-ffffffff81904fb0: __hwspin_lock_request.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
