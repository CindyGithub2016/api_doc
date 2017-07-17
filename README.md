# api_doc
基于CI框架，根据注释自动生成文档。

# 文档内容
接口，接口说明，接口参数，接口返回结果，请求模拟
#使用
实现需引入library和对应的模版，模版是使用的phalapi的模版。
eg: localhost: 127.0.0.1

<?php

    // +----------------------------------------------------------------------
    // | Author: Cindy
    // +----------------------------------------------------------------------

    defined('BASEPATH') OR exit('No direct script access allowed');

    /**
     * 接口调用控制器
     */

    class Open_api extends CI_Controller {

      /**
       * 获取奖品信息
       * @request POST open_api/get_reward_info
       * @param  int    $activity_id 活动id  required 11
       * @return int    $activity_id 活动id
       */
      public function get_reward_info() {
        ...
      }
     }

其中'open_api/get_reward_info'为请求的URL，均可按要求替换
