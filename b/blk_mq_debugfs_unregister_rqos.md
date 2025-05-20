# Function: <code>blk_mq_debugfs_unregister_rqos</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814cf3f1)
Location: block/blk-mq-debugfs.c:1020
Inline: True
Inline callers:
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register_rqos
```
**Symbols:**

```
ffffffff814cf320-ffffffff814cf341: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814fdb00)
Location: block/blk-mq-debugfs.c:942
Inline: False
```
**Symbols:**

```
ffffffff814fdb00-ffffffff814fdb21: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8151ba50)
Location: block/blk-mq-debugfs.c:942
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
```
**Symbols:**

```
ffffffff8151ba50-ffffffff8151ba71: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8157c1e0)
Location: block/blk-mq-debugfs.c:946
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
```
**Symbols:**

```
ffffffff8157c1e0-ffffffff8157c204: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81599280)
Location: block/blk-mq-debugfs.c:942
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
```
**Symbols:**

```
ffffffff81599280-ffffffff815992a4: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815a0080)
Location: block/blk-mq-debugfs.c:940
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
```
**Symbols:**

```
ffffffff815a0080-ffffffff815a00a4: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816088a0)
Location: block/blk-mq-debugfs.c:956
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
```
**Symbols:**

```
ffffffff816088a0-ffffffff816088c4: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816bc4a0)
Location: block/blk-mq-debugfs.c:816
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
```
**Symbols:**

```
ffffffff816bc4a0-ffffffff816bc4e3: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8177ce90)
Location: block/blk-mq-debugfs.c:814
Inline: False
```
**Symbols:**

```
ffffffff8177ce90-ffffffff8177ced3: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff817bc830)
Location: block/blk-mq-debugfs.c:788
Inline: False
Direct callers:
  - block/blk-rq-qos.c:rq_qos_del
```
**Symbols:**

```
ffffffff817bc830-ffffffff817bc877: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81800ef0)
Location: block/blk-mq-debugfs.c:769
Inline: False
Direct callers:
  - block/blk-rq-qos.c:rq_qos_del
```
**Symbols:**

```
ffffffff81800ef0-ffffffff81800f37: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffff8000106240a0)
Location: block/blk-mq-debugfs.c:942
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
```
**Symbols:**

```
ffff8000106240a0-ffff8000106240d0: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c07cb6dc)
Location: block/blk-mq-debugfs.c:942
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
```
**Symbols:**

```
c07cb6dc-c07cb708: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c0000000007c4bb0)
Location: block/blk-mq-debugfs.c:942
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-iocost.c:blk_iocost_init
```
**Symbols:**

```
c0000000007c4bb0-c0000000007c4bfc: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffe000455c7e)
Location: block/blk-mq-debugfs.c:942
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
```
**Symbols:**

```
ffffffe000455c7e-ffffffe000455cac: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
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
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81514030)
Location: block/blk-mq-debugfs.c:942
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
```
**Symbols:**

```
ffffffff81514030-ffffffff81514051: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81504340)
Location: block/blk-mq-debugfs.c:942
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
```
**Symbols:**

```
ffffffff81504340-ffffffff81504361: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815100c0)
Location: block/blk-mq-debugfs.c:942
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
```
**Symbols:**

```
ffffffff815100c0-ffffffff815100e1: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_debugfs_unregister_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81529880)
Location: block/blk-mq-debugfs.c:942
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
```
**Symbols:**

```
ffffffff81529880-ffffffff815298a1: blk_mq_debugfs_unregister_rqos (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
