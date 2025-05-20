# Function: <code>xs_talkv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff814cd280)
Location: drivers/xen/xenbus/xenbus_xs.c:266
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
```
**Symbols:**

```
ffffffff814cd280-ffffffff814cd470: xs_talkv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8151ddf0)
Location: drivers/xen/xenbus/xenbus_xs.c:261
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff8151ddf0-ffffffff8151dfe4: xs_talkv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154a270)
Location: drivers/xen/xenbus/xenbus_xs.c:261
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff8154a270-ffffffff8154a464: xs_talkv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155e9f0)
Location: drivers/xen/xenbus/xenbus_xs.c:293
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff8155e9f0-ffffffff8155ec88: xs_talkv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c2d20)
Location: drivers/xen/xenbus/xenbus_xs.c:295
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff815c2d20-ffffffff815c2fbf: xs_talkv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:297
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff815fb3e0-ffffffff815fb656: xs_talkv (STB_LOCAL)
ffffffff815fc69e-ffffffff815fc6cf: xs_talkv.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:297
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff81616490-ffffffff81616706: xs_talkv (STB_LOCAL)
ffffffff8161774e-ffffffff8161777f: xs_talkv.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:299
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff8164a100-ffffffff8164a3b3: xs_talkv (STB_LOCAL)
ffffffff8164b3ed-ffffffff8164b41e: xs_talkv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:302
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff8166c590-ffffffff8166c843: xs_talkv (STB_LOCAL)
ffffffff8166d87d-ffffffff8166d8ae: xs_talkv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:302
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_unwatch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff8171c840-ffffffff8171c9d3: xs_talkv (STB_LOCAL)
ffffffff8171dbc9-ffffffff8171dbfa: xs_talkv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:302
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_unwatch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff81739800-ffffffff81739993: xs_talkv (STB_LOCAL)
ffffffff81c0557a-ffffffff81c055ab: xs_talkv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:302
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff8171cfd0-ffffffff8171d2c2: xs_talkv (STB_LOCAL)
ffffffff81bf71df-ffffffff81bf7210: xs_talkv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:302
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff8179bd60-ffffffff8179c078: xs_talkv (STB_LOCAL)
ffffffff81cf60eb-ffffffff81cf611c: xs_talkv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:302
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_unwatch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff818d5390-ffffffff818d56cf: xs_talkv (STB_LOCAL)
ffffffff81ebe1d0-ffffffff81ebe201: xs_talkv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a27730)
Location: drivers/xen/xenbus/xenbus_xs.c:302
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_unwatch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff81a27730-ffffffff81a27a95: xs_talkv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a70e50)
Location: drivers/xen/xenbus/xenbus_xs.c:302
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_unwatch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff81a70e50-ffffffff81a71195: xs_talkv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac2f80)
Location: drivers/xen/xenbus/xenbus_xs.c:302
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_unwatch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff81ac2f80-ffffffff81ac32f2: xs_talkv (STB_LOCAL)
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
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffff800010836be0)
Location: drivers/xen/xenbus/xenbus_xs.c:302
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffff800010836be0-ffff800010836ec4: xs_talkv (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:302
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff81632400-ffffffff816326b3: xs_talkv (STB_LOCAL)
ffffffff816336ed-ffffffff8163371e: xs_talkv.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:302
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff816603d0-ffffffff81660683: xs_talkv (STB_LOCAL)
ffffffff816616bd-ffffffff816616ee: xs_talkv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *xs_talkv(struct xenbus_transaction t, enum xsd_sockmsg_type type, const struct kvec *iovec, unsigned int num_vecs, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (0)
Location: drivers/xen/xenbus/xenbus_xs.c:302
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:unregister_xenbus_watch
  - drivers/xen/xenbus/xenbus_xs.c:xs_watch
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_write
  - drivers/xen/xenbus/xenbus_xs.c:xs_single
```
**Symbols:**

```
ffffffff8167a9c0-ffffffff8167ac70: xs_talkv (STB_LOCAL)
ffffffff8167bc8d-ffffffff8167bcbe: xs_talkv.cold (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
