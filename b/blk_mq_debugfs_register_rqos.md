# Function: <code>blk_mq_debugfs_register_rqos</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814cf350)
Location: block/blk-mq-debugfs.c:1026
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff814cf350-ffffffff814cf43f: blk_mq_debugfs_register_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814fdb30)
Location: block/blk-mq-debugfs.c:948
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff814fdb30-ffffffff814fdbeb: blk_mq_debugfs_register_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8151ba80)
Location: block/blk-mq-debugfs.c:948
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-wbt.c:wbt_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8151ba80-ffffffff8151bb2f: blk_mq_debugfs_register_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8157c210)
Location: block/blk-mq-debugfs.c:952
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-wbt.c:wbt_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8157c210-ffffffff8157c2b2: blk_mq_debugfs_register_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815992b0)
Location: block/blk-mq-debugfs.c:948
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-wbt.c:wbt_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff815992b0-ffffffff81599352: blk_mq_debugfs_register_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815a00b0)
Location: block/blk-mq-debugfs.c:946
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-wbt.c:wbt_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff815a00b0-ffffffff815a0152: blk_mq_debugfs_register_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816088d0)
Location: block/blk-mq-debugfs.c:962
Inline: False
Direct callers:
  - block/blk-ioprio.c:blk_ioprio_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-wbt.c:wbt_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff816088d0-ffffffff81608972: blk_mq_debugfs_register_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816bc4f0)
Location: block/blk-mq-debugfs.c:826
Inline: False
Direct callers:
  - block/blk-ioprio.c:blk_ioprio_init
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-wbt.c:wbt_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff816bc4f0-ffffffff816bc5f1: blk_mq_debugfs_register_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8177cef0)
Location: block/blk-mq-debugfs.c:824
Inline: False
Direct callers:
  - block/blk-wbt.c:wbt_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff8177cef0-ffffffff8177cff1: blk_mq_debugfs_register_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff817bc890)
Location: block/blk-mq-debugfs.c:798
Inline: False
Direct callers:
  - block/blk-rq-qos.c:rq_qos_add
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff817bc890-ffffffff817bc98c: blk_mq_debugfs_register_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81800f50)
Location: block/blk-mq-debugfs.c:779
Inline: False
Direct callers:
  - block/blk-rq-qos.c:rq_qos_add
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81800f50-ffffffff8180104c: blk_mq_debugfs_register_rqos (STB_GLOBAL)
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
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffff8000106240d0)
Location: block/blk-mq-debugfs.c:948
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-wbt.c:wbt_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffff8000106240d0-ffff8000106241a4: blk_mq_debugfs_register_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c07cb708)
Location: block/blk-mq-debugfs.c:948
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-wbt.c:wbt_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
c07cb708-c07cb7bc: blk_mq_debugfs_register_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c0000000007c4c00)
Location: block/blk-mq-debugfs.c:948
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-wbt.c:wbt_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
c0000000007c4c00-c0000000007c4d24: blk_mq_debugfs_register_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffe000455cac)
Location: block/blk-mq-debugfs.c:948
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-wbt.c:wbt_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffe000455cac-ffffffe000455d5a: blk_mq_debugfs_register_rqos (STB_GLOBAL)
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
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81514060)
Location: block/blk-mq-debugfs.c:948
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-wbt.c:wbt_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81514060-ffffffff8151410f: blk_mq_debugfs_register_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81504370)
Location: block/blk-mq-debugfs.c:948
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-wbt.c:wbt_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff81504370-ffffffff8150441f: blk_mq_debugfs_register_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815100f0)
Location: block/blk-mq-debugfs.c:948
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-wbt.c:wbt_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff815100f0-ffffffff8151019f: blk_mq_debugfs_register_rqos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_debugfs_register_rqos(struct rq_qos *rqos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff815298b0)
Location: block/blk-mq-debugfs.c:948
Inline: False
Direct callers:
  - block/blk-iocost.c:blk_iocost_init
  - block/blk-wbt.c:wbt_init
  - block/blk-mq-debugfs.c:blk_mq_debugfs_register
```
**Symbols:**

```
ffffffff815298b0-ffffffff8152995f: blk_mq_debugfs_register_rqos (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
