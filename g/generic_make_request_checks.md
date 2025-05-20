# Function: <code>generic_make_request_checks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b60a0)
Location: block/blk-core.c:1915
Inline: False
```
**Symbols:**

```
ffffffff813b60a0-ffffffff813b65c9: generic_make_request_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813faef0)
Location: block/blk-core.c:1880
Inline: False
```
**Symbols:**

```
ffffffff813faef0-ffffffff813fb41e: generic_make_request_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81414830)
Location: block/blk-core.c:1854
Inline: False
```
**Symbols:**

```
ffffffff81414830-ffffffff81414dd0: generic_make_request_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81424510)
Location: block/blk-core.c:2000
Inline: False
```
**Symbols:**

```
ffffffff81424510-ffffffff81424abf: generic_make_request_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144d6d0)
Location: block/blk-core.c:2129
Inline: False
Direct callers:
  - block/blk-core.c:direct_make_request
```
**Symbols:**

```
ffffffff8144d6d0-ffffffff8144dc2b: generic_make_request_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:2247
Inline: False
Direct callers:
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
```
**Symbols:**

```
ffffffff81482560-ffffffff81482b97: generic_make_request_checks (STB_LOCAL)
ffffffff81485745-ffffffff81485769: generic_make_request_checks.cold.100 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:875
Inline: False
Direct callers:
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
```
**Symbols:**

```
ffffffff8149d410-ffffffff8149da9c: generic_make_request_checks (STB_LOCAL)
ffffffff8149ffb8-ffffffff8149ffdc: generic_make_request_checks.cold.64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:862
Inline: False
Direct callers:
  - block/blk-core.c:direct_make_request
```
**Symbols:**

```
ffffffff814cb630-ffffffff814cbc74: generic_make_request_checks (STB_LOCAL)
ffffffff814ce006-ffffffff814ce02a: generic_make_request_checks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:870
Inline: False
Direct callers:
  - block/blk-core.c:direct_make_request
```
**Symbols:**

```
ffffffff814e4820-ffffffff814e4eb2: generic_make_request_checks (STB_LOCAL)
ffffffff814e7326-ffffffff814e734a: generic_make_request_checks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:957
Inline: False
Direct callers:
  - block/blk-core.c:direct_make_request
```
**Symbols:**

```
ffffffff815447c0-ffffffff81544cf1: generic_make_request_checks (STB_LOCAL)
ffffffff81546358-ffffffff8154637c: generic_make_request_checks.cold (STB_LOCAL)
```
</details>
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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e2b48)
Location: block/blk-core.c:870
Inline: False
Direct callers:
  - block/blk-core.c:direct_make_request
```
**Symbols:**

```
ffff8000105e2b48-ffff8000105e319c: generic_make_request_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078ee84)
Location: block/blk-core.c:870
Inline: False
Direct callers:
  - block/blk-core.c:direct_make_request
  - block/blk-core.c:generic_make_request
```
**Symbols:**

```
c078ee84-c078f688: generic_make_request_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c0000000007750a0)
Location: block/blk-core.c:870
Inline: False
Direct callers:
  - block/blk-core.c:direct_make_request
```
**Symbols:**

```
c0000000007750a0-c0000000007758dc: generic_make_request_checks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000423e90)
Location: block/blk-core.c:870
Inline: False
Direct callers:
  - block/blk-core.c:direct_make_request
```
**Symbols:**

```
ffffffe000423e90-ffffffe00042441c: generic_make_request_checks (STB_LOCAL)
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
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:870
Inline: False
Direct callers:
  - block/blk-core.c:direct_make_request
```
**Symbols:**

```
ffffffff814dce00-ffffffff814dd492: generic_make_request_checks (STB_LOCAL)
ffffffff814df906-ffffffff814df92a: generic_make_request_checks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:870
Inline: False
Direct callers:
  - block/blk-core.c:direct_make_request
```
**Symbols:**

```
ffffffff814cd7b0-ffffffff814cde3d: generic_make_request_checks (STB_LOCAL)
ffffffff814d02a6-ffffffff814d02ca: generic_make_request_checks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:870
Inline: False
Direct callers:
  - block/blk-core.c:direct_make_request
```
**Symbols:**

```
ffffffff814d8e90-ffffffff814d9522: generic_make_request_checks (STB_LOCAL)
ffffffff814db996-ffffffff814db9ba: generic_make_request_checks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool generic_make_request_checks(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-core.c (0)
Location: block/blk-core.c:870
Inline: False
Direct callers:
  - block/blk-core.c:direct_make_request
```
**Symbols:**

```
ffffffff814f1aa0-ffffffff814f21bd: generic_make_request_checks (STB_LOCAL)
ffffffff814f4806-ffffffff814f482f: generic_make_request_checks.cold (STB_LOCAL)
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
