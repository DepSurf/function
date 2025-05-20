# Function: <code>bsg_teardown_job</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814454f7)
Location: block/bsg-lib.c:35
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bsg_teardown_job(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81471fb0)
Location: block/bsg-lib.c:35
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_softirq_done
```
**Symbols:**

```
ffffffff81471fb0-ffffffff81471fed: bsg_teardown_job (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bsg_teardown_job(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814a6400)
Location: block/bsg-lib.c:123
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_softirq_done
```
**Symbols:**

```
ffffffff814a6400-ffffffff814a6439: bsg_teardown_job (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bsg_teardown_job(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814c0430)
Location: block/bsg-lib.c:128
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_complete
```
**Symbols:**

```
ffffffff814c0430-ffffffff814c0469: bsg_teardown_job (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bsg_teardown_job(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814eeb10)
Location: block/bsg-lib.c:148
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_complete
```
**Symbols:**

```
ffffffff814eeb10-ffffffff814eeb49: bsg_teardown_job (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bsg_teardown_job(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81507f70)
Location: block/bsg-lib.c:148
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_complete
```
**Symbols:**

```
ffffffff81507f70-ffffffff81507fa9: bsg_teardown_job (STB_LOCAL)
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
In block/bsg-lib.c (ffffffff8156992a)
Location: block/bsg-lib.c:148
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
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
In block/bsg-lib.c (ffffffff8158426a)
Location: block/bsg-lib.c:148
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
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
In block/bsg-lib.c (ffffffff8158affa)
Location: block/bsg-lib.c:148
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
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
In block/bsg-lib.c (ffffffff815f006a)
Location: block/bsg-lib.c:149
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
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
In block/bsg-lib.c (ffffffff816a1003)
Location: block/bsg-lib.c:156
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
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
In block/bsg-lib.c (ffffffff8175fbf3)
Location: block/bsg-lib.c:156
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
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
In block/bsg-lib.c (ffffffff8179ead3)
Location: block/bsg-lib.c:156
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
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
In block/bsg-lib.c (ffffffff817e25b3)
Location: block/bsg-lib.c:156
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_complete
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
In block/bsg-lib.c (ffff80001060ab80)
Location: block/bsg-lib.c:148
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_put
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
In block/bsg-lib.c (c07b59d4)
Location: block/bsg-lib.c:148
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_put
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
In block/bsg-lib.c (c0000000007a6fc8)
Location: block/bsg-lib.c:148
Inline: True
Inline callers:
  - block/bsg-lib.c:bsg_job_put
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bsg_teardown_job(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffe000443bf4)
Location: block/bsg-lib.c:148
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_complete
```
**Symbols:**

```
ffffffe000443bf4-ffffffe000443c42: bsg_teardown_job (STB_LOCAL)
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
void bsg_teardown_job(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81500550)
Location: block/bsg-lib.c:148
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_complete
```
**Symbols:**

```
ffffffff81500550-ffffffff81500589: bsg_teardown_job (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bsg_teardown_job(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814f0a60)
Location: block/bsg-lib.c:148
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_complete
```
**Symbols:**

```
ffffffff814f0a60-ffffffff814f0a99: bsg_teardown_job (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bsg_teardown_job(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814fc5e0)
Location: block/bsg-lib.c:148
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_complete
```
**Symbols:**

```
ffffffff814fc5e0-ffffffff814fc619: bsg_teardown_job (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bsg_teardown_job(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81515690)
Location: block/bsg-lib.c:148
Inline: False
Direct callers:
  - block/bsg-lib.c:bsg_complete
```
**Symbols:**

```
ffffffff81515690-ffffffff815156c9: bsg_teardown_job (STB_LOCAL)
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
</ul>
<b>Arch</b>
<ul>
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
