# complete-seaborn-crash-course
This is complete course of Seaborn Watch it Here Live in Free-> https://www.youtube.com/watch?v=GcXcSZ0gQps 

You can add labels to data as follows

sns.relplot(x = 'timepoint', y = 'signal', kind = 'line', data = fmri, ci = False, label='Signal', height=4, aspect=2)
plt.legend(loc='center left',bbox_to_anchor=(0.5,0.5))
plt.show()
