# Function: <code>starget_for_each_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815a68c0)
Location: drivers/scsi/scsi.c:979
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
```
**Symbols:**

```
ffffffff815a68c0-ffffffff815a6975: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815feb50)
Location: drivers/scsi/scsi.c:994
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff815feb50-ffffffff815fec05: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8162e1a0)
Location: drivers/scsi/scsi.c:997
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff8162e1a0-ffffffff8162e255: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81643590)
Location: drivers/scsi/scsi.c:638
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff81643590-ffffffff81643645: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816ac6a0)
Location: drivers/scsi/scsi.c:618
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff816ac6a0-ffffffff816ac757: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816e8bd0)
Location: drivers/scsi/scsi.c:618
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff816e8bd0-ffffffff816e8c87: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8170c6d0)
Location: drivers/scsi/scsi.c:618
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff8170c6d0-ffffffff8170c77f: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81747de0)
Location: drivers/scsi/scsi.c:598
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff81747de0-ffffffff81747e6c: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8176bf30)
Location: drivers/scsi/scsi.c:598
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff8176bf30-ffffffff8176bfbc: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8182e720)
Location: drivers/scsi/scsi.c:588
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff8182e720-ffffffff8182e804: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8183f760)
Location: drivers/scsi/scsi.c:588
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff8183f760-ffffffff8183f844: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818229c0)
Location: drivers/scsi/scsi.c:601
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff818229c0-ffffffff81822aaa: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818ad300)
Location: drivers/scsi/scsi.c:598
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff818ad300-ffffffff818ad3ea: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff819f7d40)
Location: drivers/scsi/scsi.c:631
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff819f7d40-ffffffff819f7e39: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81b75640)
Location: drivers/scsi/scsi.c:631
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff81b75640-ffffffff81b75739: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81bc8f70)
Location: drivers/scsi/scsi.c:787
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff81bc8f70-ffffffff81bc9069: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81c1de60)
Location: drivers/scsi/scsi.c:816
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff81c1de60-ffffffff81c1df59: starget_for_each_device (STB_GLOBAL)
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
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffff80001096e5c8)
Location: drivers/scsi/scsi.c:598
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffff80001096e5c8-ffff80001096e680: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c0a439c0)
Location: drivers/scsi/scsi.c:598
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
c0a439c0-c0a43a64: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c000000000a27540)
Location: drivers/scsi/scsi.c:598
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
c000000000a27540-c000000000a27654: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffe0005d87ac)
Location: drivers/scsi/scsi.c:598
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffe0005d87ac-ffffffe0005d8846: starget_for_each_device (STB_GLOBAL)
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
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81720620)
Location: drivers/scsi/scsi.c:598
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff81720620-ffffffff817206ac: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816f9a50)
Location: drivers/scsi/scsi.c:598
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff816f9a50-ffffffff816f9adc: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8175f3f0)
Location: drivers/scsi/scsi.c:598
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff8175f3f0-ffffffff8175f47c: starget_for_each_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void starget_for_each_device(struct scsi_target *starget, void *data, void (*fn)(struct scsi_device *, void *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8177aa50)
Location: drivers/scsi/scsi.c:598
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_target_unblock
  - drivers/scsi/scsi_lib.c:scsi_target_resume
  - drivers/scsi/scsi_lib.c:scsi_target_quiesce
```
**Symbols:**

```
ffffffff8177aa50-ffffffff8177aadc: starget_for_each_device (STB_GLOBAL)
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
