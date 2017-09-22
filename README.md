# drag
自定义拖拽，轻微兼容移动端！
    $(element).each(function(){
          $(this).dragging({
                move : 'both',
                randomPosition : false ,
                hander:'.hander'
        });
      });
