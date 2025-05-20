# Function: <code>__list_splice_init_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8139b33a)
Location: include/linux/rculist.h:200
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff813b8cdd)
Location: include/linux/rculist.h:200
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813b202a)
Location: include/linux/rculist.h:198
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff813d009d)
Location: include/linux/rculist.h:198
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813c862a)
Location: include/linux/rculist.h:198
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff813e3930)
Location: include/linux/rculist.h:198
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff813eeaba)
Location: include/linux/rculist.h:199
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff8140a720)
Location: include/linux/rculist.h:199
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8141fb6b)
Location: include/linux/rculist.h:199
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff8143bf30)
Location: include/linux/rculist.h:199
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff81454c4d)
Location: include/linux/rculist.h:199
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8143c63b)
Location: include/linux/rculist.h:199
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff81458da0)
Location: include/linux/rculist.h:199
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff81471f1d)
Location: include/linux/rculist.h:199
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8146a1f7)
Location: include/linux/rculist.h:199
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff81486520)
Location: include/linux/rculist.h:199
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff8149fb8d)
Location: include/linux/rculist.h:199
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81483fd7)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff814a03d0)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff814ba13d)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff814da127)
Location: include/linux/rculist.h:227
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff814fa25c)
Location: include/linux/rculist.h:227
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff8151a34d)
Location: include/linux/rculist.h:227
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff814f76d4)
Location: include/linux/rculist.h:235
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff81516fdc)
Location: include/linux/rculist.h:235
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff815373cd)
Location: include/linux/rculist.h:235
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff814fe304)
Location: include/linux/rculist.h:235
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff8151d88c)
Location: include/linux/rculist.h:235
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff8153fabd)
Location: include/linux/rculist.h:235
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81559064)
Location: include/linux/rculist.h:226
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff8157b97c)
Location: include/linux/rculist.h:226
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff8159f0ad)
Location: include/linux/rculist.h:226
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff815f43c1)
Location: include/linux/rculist.h:226
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff81619f60)
Location: include/linux/rculist.h:226
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff81644a2d)
Location: include/linux/rculist.h:226
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff816a4d61)
Location: include/linux/rculist.h:226
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff816cd240)
Location: include/linux/rculist.h:226
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff816fcecd)
Location: include/linux/rculist.h:226
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff816dd741)
Location: include/linux/rculist.h:226
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff81705950)
Location: include/linux/rculist.h:226
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff81736efd)
Location: include/linux/rculist.h:226
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81719621)
Location: include/linux/rculist.h:226
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff81743250)
Location: include/linux/rculist.h:226
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff817779bd)
Location: include/linux/rculist.h:226
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffff800010575e88)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffff8000105961a4)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (0)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (c0728804)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (c0747270)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (c0761be8)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (c0000000006df598)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (c00000000070bb94)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (c000000000733b3c)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffe0003c8cd8)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffe0003e2e1c)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffe0003f9d5e)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8147c5b7)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff814989b0)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff814b271d)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff8146cfd7)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff814893d0)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff814a313d)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81478657)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff81494a50)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff814ae7ad)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smackfs.c (ffffffff81490107)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/smack/smackfs.c:smk_write_onlycap
```
```
In security/apparmor/policy.c (ffffffff814aca70)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/apparmor/policy.c:__replace_profile
```
```
In security/integrity/ima/ima_policy.c (ffffffff814c71fd)
Location: include/linux/rculist.h:217
Inline: True
Inline callers:
  - security/integrity/ima/ima_policy.c:ima_update_policy
```
</details>
</li>
</ul>

## Differences
