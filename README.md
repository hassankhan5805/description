Audio controller file ma line 105 mai play(false); likha hai jis k bad aap session complete ka event registr kr
skty ho session k nam ka 
UserServices().updateUser({
              "watchedCourses":
                  FieldValue.arrayUnion([user.user.value.currentCourseID])
            });
( audio.name mai session ka name aa ra ho ga but check kr lna print kr k 1dfa)
phr isi file ma line 82 ma aap dkh skty ho mai na user k cimplete course ma 1 new id add ki hai us courseki
jo abi complete hua idr aap complete course ka event register jis k lia aap user.user.value.currentCourseIDuse kr lo
