# week-1-b-frequency-polygon
#frequency polygon.
#c <- c(7,20,30,76,3,4,23,14,67)
Names <- c("pragnaL","swathi","SATWIKA","NITHYA","lohitha")
Rollno <- c("Y20CS093","Y20CS123","Y20CS149","Y20CS127","Y20CS095")
Gender <- c("Female","Female","Female","Female","Female")
Marks <-c(9,3,6,8,9)
Fee <-c(69400,57892,58903,69400,67390)
Section <-c("C","B","C","B","B")

rvrstudents <-data.frame(Names,Rollno,Gender,Marks,Fee,Section)
rvrstudents
write.csv(rvrstudents,"Rvr_Students.csv",row.names=F)

a <- read.csv("Rvr_Students.csv")


plot(rvrstudents$Marks,type="o",xlab="students names",ylab="students marks",xlim=c(1,10),ylim=c(0,40),main="RVRJC COLLEGE OF ENGINEERING.",col="green")



OUTPUT:
> #frequency polygon.
> #c <- c(7,20,30,76,3,4,23,14,67)
> Names <- c("pragna","swathi","SATWIKA","NITHYA","lohitha")
> Rollno <- c("Y20CS093","Y20CS123","Y20CS149","Y20CS127","Y20CS095")
> Gender <- c("Female","Female","Female","Female","Female")
> Marks <-c(9,3,6,8,9)
> Fee <-c(69400,57892,58903,69400,67390)
> Section <-c("C","B","C","B","B")
> rvrstudents <-data.frame(Names,Rollno,Gender,Marks,Fee,Section)
> rvrstudents
    Names   Rollno Gender Marks   Fee Section
1  pragna Y20CS093   Female     9 69400       C
2   swathi Y20CS123 Female     3 57892       B
3 SATWIKA Y20CS149 Female     6 58903       C
4  NITHYA Y20CS127 Female     8 69400       B
5   lohitha Y20CS095   FEmale     9 67390       B
> write.csv(rvrstudents,"Rvr_Students.csv",row.names=F)
> a <- read.csv("Rvr_Students.csv")
> plot(rvrstudents$Marks,type="o",xlab="students names",ylab="students marks",xlim=c(1,10),ylim=c(0,40),main="RVRJC COLLEGE OF ENGINEERING.",col="green")
> 
