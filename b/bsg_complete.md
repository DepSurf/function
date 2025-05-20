# Function: <code>bsg_complete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool bsg_complete(struct bsg_device *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff813d6240)
Location: block/bsg.c:449
Inline: False
Direct callers:
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_release
```
**Symbols:**

```
ffffffff813d6240-ffffffff813d629c: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool bsg_complete(struct bsg_device *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff8141bf40)
Location: block/bsg.c:449
Inline: False
Direct callers:
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_release
```
**Symbols:**

```
ffffffff8141bf40-ffffffff8141bf9b: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool bsg_complete(struct bsg_device *bd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81437750)
Location: block/bsg.c:449
Inline: False
Direct callers:
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_release
```
**Symbols:**

```
ffffffff81437750-ffffffff814377a4: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool bsg_complete(struct bsg_device *bd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81444f10)
Location: block/bsg.c:443
Inline: True
Direct callers:
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_release
```
**Symbols:**

```
ffffffff81444f10-ffffffff81444f64: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool bsg_complete(struct bsg_device *bd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814719e0)
Location: block/bsg.c:443
Inline: True
Direct callers:
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_release
```
**Symbols:**

```
ffffffff814719e0-ffffffff81471a34: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool bsg_complete(struct bsg_device *bd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814a5680)
Location: block/bsg.c:401
Inline: True
Direct callers:
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_release
```
**Symbols:**

```
ffffffff814a5680-ffffffff814a56d4: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814c0a20)
Location: block/bsg-lib.c:174
Inline: False
```
**Symbols:**

```
ffffffff814c0a20-ffffffff814c0a4b: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814ef060)
Location: block/bsg-lib.c:194
Inline: False
```
**Symbols:**

```
ffffffff814ef060-ffffffff814ef08a: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81508510)
Location: block/bsg-lib.c:194
Inline: False
```
**Symbols:**

```
ffffffff81508510-ffffffff8150853a: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81569900)
Location: block/bsg-lib.c:194
Inline: False
```
**Symbols:**

```
ffffffff81569900-ffffffff81569977: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81584240)
Location: block/bsg-lib.c:197
Inline: False
```
**Symbols:**

```
ffffffff81584240-ffffffff815842b7: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff8158afd0)
Location: block/bsg-lib.c:197
Inline: False
```
**Symbols:**

```
ffffffff8158afd0-ffffffff8158b047: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff815f0040)
Location: block/bsg-lib.c:198
Inline: False
```
**Symbols:**

```
ffffffff815f0040-ffffffff815f00b7: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff816a0fd0)
Location: block/bsg-lib.c:205
Inline: False
```
**Symbols:**

```
ffffffff816a0fd0-ffffffff816a1062: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff8175fbc0)
Location: block/bsg-lib.c:205
Inline: False
```
**Symbols:**

```
ffffffff8175fbc0-ffffffff8175fc52: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff8179eaa0)
Location: block/bsg-lib.c:205
Inline: False
```
**Symbols:**

```
ffffffff8179eaa0-ffffffff8179eb32: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff817e2580)
Location: block/bsg-lib.c:205
Inline: False
```
**Symbols:**

```
ffffffff817e2580-ffffffff817e2612: bsg_complete (STB_LOCAL)
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
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffff80001060abb0)
Location: block/bsg-lib.c:194
Inline: False
```
**Symbols:**

```
ffff80001060abb0-ffff80001060abdc: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (c07b59fc)
Location: block/bsg-lib.c:194
Inline: False
```
**Symbols:**

```
c07b59fc-c07b5a1c: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (c0000000007a7020)
Location: block/bsg-lib.c:194
Inline: False
```
**Symbols:**

```
c0000000007a7020-c0000000007a7038: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffe000443c86)
Location: block/bsg-lib.c:194
Inline: False
```
**Symbols:**

```
ffffffe000443c86-ffffffe000443cca: bsg_complete (STB_LOCAL)
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
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81500af0)
Location: block/bsg-lib.c:194
Inline: False
```
**Symbols:**

```
ffffffff81500af0-ffffffff81500b1a: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814f1000)
Location: block/bsg-lib.c:194
Inline: False
```
**Symbols:**

```
ffffffff814f1000-ffffffff814f102a: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814fcb80)
Location: block/bsg-lib.c:194
Inline: False
```
**Symbols:**

```
ffffffff814fcb80-ffffffff814fcbaa: bsg_complete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bsg_complete(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81515c30)
Location: block/bsg-lib.c:194
Inline: False
```
**Symbols:**

```
ffffffff81515c30-ffffffff81515c5a: bsg_complete (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request *rq</code>
</li>
<li>
<b>Param removed. </b>
<code>struct bsg_device *bd</code>
</li>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
