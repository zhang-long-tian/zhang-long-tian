### Hi there 👋
nice to meet you🤝  
PISCES Birth:2001.2.24🐍  
张龑(Mark)，a univesity student ,20grade  
character：optimistic    
Now,I am single. Favourite color:green and blue   
I only learn a bit programming language.  
I like playing sports and listening to music.   
In the future,I will try my best on studying.    
Only in this way can I climbed to the summit of the mountain!  
QQ:247880503
new GuideViewHelper(MainActivity.this)
                .addView(btn_light1, new RightTopStyle(deco_view1))
                .addView(tv_light2, new CenterRightStyle(deco_view2))
                .addView(tv_light3, new LeftBottomStyle(deco_view3, 10))
                .addView(iv_light4, new CenterTopStyle(deco_view4, 10))
                .type(LightType.Oval)
                .autoNext()
                .onDismiss(new GuideView.OnDismissListener() {
                    @Override
                    public void dismiss() {
                    }
                })
                .show();
