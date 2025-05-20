# Function: <code>destruct_tty_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e0090)
Location: drivers/tty/tty_io.c:3426
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:release_one_tty
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_open
```
**Symbols:**

```
ffffffff814e0090-ffffffff814e015b: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815318c0)
Location: drivers/tty/tty_io.c:3422
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff815318c0-ffffffff8153198b: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155e000)
Location: drivers/tty/tty_io.c:3422
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff8155e000-ffffffff8155e0cb: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81572f84)
Location: drivers/tty/tty_io.c:2980
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_driver_kref_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d7300)
Location: drivers/tty/tty_io.c:3087
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff815d7300-ffffffff815d73c3: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816102b0)
Location: drivers/tty/tty_io.c:3108
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff816102b0-ffffffff81610373: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162d0b0)
Location: drivers/tty/tty_io.c:3263
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff8162d0b0-ffffffff8162d173: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81660d10)
Location: drivers/tty/tty_io.c:3267
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81660d10-ffffffff81660dd3: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81683360)
Location: drivers/tty/tty_io.c:3263
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81683360-ffffffff81683423: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81734240)
Location: drivers/tty/tty_io.c:3266
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81734240-ffffffff81734303: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81750390)
Location: drivers/tty/tty_io.c:3359
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open_by_driver
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81750390-ffffffff81750453: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81734210)
Location: drivers/tty/tty_io.c:3408
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81734210-ffffffff817342d3: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b4b70)
Location: drivers/tty/tty_io.c:3408
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff817b4b70-ffffffff817b4c33: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f0990)
Location: drivers/tty/tty_io.c:3375
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff818f0990-ffffffff818f0a5f: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a48b50)
Location: drivers/tty/tty_io.c:3372
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81a48b50-ffffffff81a48c1a: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a92da0)
Location: drivers/tty/tty_io.c:3378
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81a92da0-ffffffff81a92e6a: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae57f0)
Location: drivers/tty/tty_io.c:3395
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:tty_lookup_driver
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81ae57f0-ffffffff81ae58ba: destruct_tty_driver (STB_LOCAL)
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
In drivers/tty/tty_io.c (ffff80001084f974)
Location: drivers/tty/tty_io.c:3263
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_driver_kref_put
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
In drivers/tty/tty_io.c (c095b994)
Location: drivers/tty/tty_io.c:3263
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_driver_kref_put
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
In drivers/tty/tty_io.c (c0000000008efad0)
Location: drivers/tty/tty_io.c:3263
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_driver_kref_put
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052ddbe)
Location: drivers/tty/tty_io.c:3263
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffe00052ddbe-ffffffe00052de9c: destruct_tty_driver (STB_LOCAL)
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
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81648de0)
Location: drivers/tty/tty_io.c:3263
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81648de0-ffffffff81648ea3: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81629240)
Location: drivers/tty/tty_io.c:3263
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff81629240-ffffffff81629303: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816771a0)
Location: drivers/tty/tty_io.c:3263
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff816771a0-ffffffff81677263: destruct_tty_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void destruct_tty_driver(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816918c0)
Location: drivers/tty/tty_io.c:3263
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:put_tty_driver
  - drivers/tty/tty_io.c:tty_open
  - drivers/tty/tty_io.c:tty_kopen
  - drivers/tty/tty_io.c:release_one_tty
```
**Symbols:**

```
ffffffff816918c0-ffffffff81691983: destruct_tty_driver (STB_LOCAL)
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
