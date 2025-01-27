# 成员列表
这是LeonMMcoset团队和跟LeonMMcoset合作的成员信息。

## Leon中央组
<script setup>
//The player list of LeonMMcoset Team.
// ---LeonMMcoset论坛---
// { icon: {svg: leonbbs}, link: 'http://leonmmcoset.jjmm.ink:1000/web/bbs/public/u/1' }
import { VPTeamMembers } from 'vitepress/theme'
import { bilibili, email, qq, leonbbs } from '.vitepress/icon.mts'
const membersA = [
  {
    avatar: 'https://www.github.com/leonmmcoset.png',
    name: 'LeonMMcoset',
    title: '团队首领',
    links: [
      { icon: 'github', link: 'https://github.com/leonmmcoset' },
      { icon: {svg: qq}, link: '/vitepress/qq' },
      { icon: {svg: bilibili}, link: 'https://space.bilibili.com/245143694?spm_id_from=333.337.0.0'},
      { icon: {svg: email}, link: 'mailto:leonmmcoset@outlook.com'},
      { icon: {svg: leonbbs}, link: 'http://leonmmcoset.jjmm.ink:1000/web/bbs/public/u/1' }
    ]
  },
  {
    avatar: 'https://github.com/Leonmmcoset/vitepress/blob/main/images/Yeonmmcoset-2.png?raw=true',
    name: 'Yeonmmcoset',
    title: '团队成员',
    links: [
      { icon: {svg: bilibili}, link: 'https://space.bilibili.com/3546601461123155?spm_id_from=333.337.0.0'},
      { icon: {svg: email}, link: 'mailto:yeonmmcoset@outlook.com'}
    ]
  },
  {
    avatar: 'https://github.com/Leonmmcoset/vitepress/blob/3c0cb70b27473534b7c10e6bd729e4980c81429c/images/hushu.png?raw=true',
    name: 'hushu',
    title: '团队成员',
    links: [
      { icon: {svg: bilibili}, link: 'https://space.bilibili.com/3546650649823421?spm_id_from=333.337.0.0'}
    ]
  }
]
// const membersB = [
//   {
//     avatar: 'https://github.com/Leonmmcoset/vitepress/blob/3c0cb70b27473534b7c10e6bd729e4980c81429c/images/hushu.png?raw=true',
//     name: 'hushu',
//     title: '群管理 | 服务器管理',
//     links: [
//       { icon: {svg: bilibili}, link: 'https://space.bilibili.com/3546650649823421?spm_id_from=333.337.0.0'}
//     ]
//   },
//   {
//     avatar: 'http://leonmmcoset.jjmm.ink:1000/web/bbs/public/assets/avatars/enOte4hqLSiMybfl.png',
//     name: 'wjdyd',
//     title: '论坛总管',
//     links: [
//       { icon: {svg: leonbbs}, link: 'http://leonmmcoset.jjmm.ink:1000/web/bbs/public/u/6' }
//     ]
//   },
//   {
//     avatar: 'http://q.qlogo.cn/headimg_dl?dst_uin=3639023079&spec=640&img_type=jpg',
//     name: 'spentwing672136',
//     title: '群管理',
//     links: [
//       { icon: {svg: leonbbs}, link: 'http://leonmmcoset.jjmm.ink:1000/web/bbs/public/u/6' }
//     ]
//   },
//   {
//     avatar: 'http://q.qlogo.cn/headimg_dl?dst_uin=2667727093&spec=640&img_type=jpg',
//     name: 'xiaozhecun1048',
//     title: '服务器管理',
//     links: [
//       { icon: {svg: leonbbs}, link: 'http://leonmmcoset.jjmm.ink:1000/web/bbs/public/u/7' }
//     ]
//   },
//   {
//     avatar: 'http://q.qlogo.cn/headimg_dl?dst_uin=3522947244&spec=640&img_type=jpg',
//     name: 'linfeng',
//     title: '服务器管理 | 论坛管理',
//     links: [
//       { icon: {svg: leonbbs}, link: 'http://leonmmcoset.jjmm.ink:1000/web/bbs/public/u/30' }
//     ]
//   },
//   {
//     avatar: 'http://leonmmcoset.jjmm.ink:1000/web/bbs/public/assets/avatars/kfvQTsB0lzfrEI8j.png',
//     name: 'anythingpea',
//     title: '群管理 | 服务器管理',
//     links: [
//       { icon: {svg: leonbbs}, link: 'http://leonmmcoset.jjmm.ink:1000/web/bbs/public/u/9' }
//     ]
//   },
// ]
</script>
<VPTeamMembers size="medium" :members="membersA" />

## Leon轨道交通管理组
<script>
import { VPTeamMembers } from 'vitepress/theme'
import { bilibili, email, qq, leonbbs } from '.vitepress/icon.mts'
const membersB = [
  {
    avatar: 'https://github.com/Leonmmcoset/vitepress/blob/3c0cb70b27473534b7c10e6bd729e4980c81429c/images/hushu.png?raw=true',
    name: 'hushu',
    title: '群管理 | 服务器管理',
    links: [
      { icon: {svg: bilibili}, link: 'https://space.bilibili.com/3546650649823421?spm_id_from=333.337.0.0'}
    ]
  },
  {
    avatar: 'http://q.qlogo.cn/headimg_dl?dst_uin=104560298&spec=640&img_type=jpg',
    name: 'wjdyd',
    title: '论坛总管',
    links: [
      { icon: {svg: leonbbs}, link: 'http://leonmmcoset.jjmm.ink:1000/web/bbs/public/u/6' }
    ]
  },
  {
    avatar: 'http://q.qlogo.cn/headimg_dl?dst_uin=3639023079&spec=640&img_type=jpg',
    name: 'spentwing672136',
    title: '群管理',
    links: [
      { icon: {svg: leonbbs}, link: 'http://leonmmcoset.jjmm.ink:1000/web/bbs/public/u/6' }
    ]
  },
  {
    avatar: 'http://q.qlogo.cn/headimg_dl?dst_uin=2667727093&spec=640&img_type=jpg',
    name: 'xiaozhecun1048',
    title: '服务器管理',
    links: [
      { icon: {svg: leonbbs}, link: 'http://leonmmcoset.jjmm.ink:1000/web/bbs/public/u/7' }
    ]
  },
  {
    avatar: 'http://q.qlogo.cn/headimg_dl?dst_uin=3522947244&spec=640&img_type=jpg',
    name: 'linfeng',
    title: '服务器管理 | 论坛管理',
    links: [
      { icon: {svg: leonbbs}, link: 'http://leonmmcoset.jjmm.ink:1000/web/bbs/public/u/30' }
    ]
  },
  {
    avatar: 'http://q.qlogo.cn/headimg_dl?dst_uin=470611337&spec=640&img_type=jpg',
    name: 'anythingpea',
    title: '群管理 | 服务器管理',
    links: [
      { icon: {svg: leonbbs}, link: 'http://leonmmcoset.jjmm.ink:1000/web/bbs/public/u/9' }
    ]
  },
]
</script>
<VPTeamMembers size="medium" :members="membersB" />