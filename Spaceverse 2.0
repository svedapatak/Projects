import os
import tkinter as Tk
from tkinter import *
from PIL import ImageTk,Image
from tkinter import messagebox
from tkinter import Button
from tkinter import Label
from tkinter import Entry
from tkinter import ttk


def tarddestroy():
    tardis.destroy()
    space1()

def satdestroy():
    tardis.destroy()
    sat1()

def en():
    end=Tk()
    end.title("STAY CURIOUS AND EXPLORE")
    end.geometry("500x500")
    endim=Image.open(r"D:\spaceverse\its-a-crazy-world-out-there-be-curious.jpg")
    endim2=endim.resize((500,500),Image.ANTIALIAS)
    endim1=ImageTk.PhotoImage(endim2)
    endlabel=Label(image=endim1)
    endlabel.place(x=0,y=0)
    but=Button(end,text="STAY CURIOUS AND EXIT",font=("helvetica",12),command=end.destroy)
    but.place(rely=0.8,relx=0.3)
    end.mainloop()

def exisat():
    sat.destroy()
    en()
def exispa():
    space.destroy()
    en()
def exitard():
    tardis.destroy()
    en()


def space1():
    global space
    space=Tk()
    space.title("SOLAR SYSTEM")
    space.geometry("1250x600")
    spaceim=Image.open(r"D:\spaceverse\space.jpg")
    spaceim2=spaceim.resize((1250,600),Image.ANTIALIAS)
    spaceim1=ImageTk.PhotoImage(spaceim2)
    spacelabel=Label(image=spaceim1)
    spacelabel.place(x=0,y=0)

    def sun1():
        global sun
        sun = Toplevel(space)
        sun.title("SUN")
        sun.geometry("300x400")
        sun.config(bg="#0F0860")

        global sunme
        global sunme2
        sunpop_label=Label(sun,text="The Sun is 109 times\n wider than the Earth and 330,000 \ntimes as massive.....",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        sunmy_frame= Frame(sun,bg="#0F0860")
        sunmy_frame.pack(pady=5)
        sunmep=Image.open(r"D:\spaceverse\sun.jpg")
        sunmep=sunmep.resize((100,100),Image.ANTIALIAS)
        sunme=ImageTk.PhotoImage(sunmep)
        sunmep1=Image.open(r"D:\spaceverse\sunqr.png")
        sunmep1=sunmep1.resize((100,100),Image.ANTIALIAS)
        sunme2=ImageTk.PhotoImage(sunmep1)
        sunl=Label(sunmy_frame,image=sunme)
        sunl.grid(row=0,column=0,padx=10)
        sunqr=Label(sunmy_frame,image=sunme2)
        sunqr.grid(row=1,column=0,padx=10)

        sunme_pic=Label(sunmy_frame,image=sunme)
        sunme_pic.grid(row=0,column=0,padx=10)
        sunme1_pic=Label(sunmy_frame,image=sunme2)
        sunme1_pic.grid(row=1,column=0,padx=10)
        dlab=Label(sun,text="To find your weight\n on Sun \n write your weight bellow \n and find out:",bg="#0F0860",fg="white")
        dlab.pack()
        en=Entry(sun)
        en.pack()
        def getd():
            a=int(en.get())
            wt="your weight on the sun is"+str(a*27.9)+"Kg"
            ml=Label(sun,text=wt,bg="#0F0860",fg="white")
            ml.pack()
        but=Button(sun,text="CALCULATE WEIGHT",command=getd)
        but.pack()
        q=Button(sunmy_frame, text="QUIT",command=sun.destroy)
        q.grid(row=0,column=2)


    sunmy_button=Button(space,text="SUN",command=sun1,bg="#195267",fg="#F0BE25",width=4)
    sunmy_button.place(rely = 0.6,relx=0.118)


    def mercury1():
        global mercury
        mercury = Toplevel(space)
        mercury.title("MERCURY")
        mercury.geometry("300x400")
        mercury.config(bg="#0F0860")

        global mercuryme
        global mercuryme2
        mercurypop_label=Label(mercury,text="Not only is Mercury\n the smallest planet, \nit is also shrinking!",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        mercurymy_frame= Frame(mercury,bg="#0F0860")
        mercurymy_frame.pack(pady=5)
        mercurymep=Image.open(r"D:\spaceverse\mercury.jpg")
        mercurymep=mercurymep.resize((100,100),Image.ANTIALIAS)
        mercuryme=ImageTk.PhotoImage(mercurymep)
        mercurymep1=Image.open(r"D:\spaceverse\mer_curryqr.png")
        mercurymep1=mercurymep1.resize((100,100),Image.ANTIALIAS)
        mercuryme2=ImageTk.PhotoImage(mercurymep1)
        mercuryl=Label(mercurymy_frame,image=mercuryme)
        mercuryl.grid(row=0,column=0,padx=10)
        mercuryqr=Label(mercurymy_frame,image=mercuryme2)
        mercuryqr.grid(row=1,column=0,padx=10)

        mercuryme_pic=Label(mercurymy_frame,image=mercuryme)
        mercuryme_pic.grid(row=0,column=0,padx=10)
        mercuryme1_pic=Label(mercurymy_frame,image=mercuryme2)
        mercuryme1_pic.grid(row=1,column=0,padx=10)
        dlab=Label(mercury,text="To find your weight\n on Mercury\n write your weight bellow \n and find out:",bg="#0F0860",fg="white")
        dlab.pack()
        en=Entry(mercury)
        en.pack()
        def getd():
            a=int(en.get())
            wt="your weight on Mercury is"+str(a*0.38)+"Kg"
            ml=Label(mercury,text=wt,bg="#0F0860",fg="white")
            ml.pack()
        but=Button(mercury,text="CALCULATE",command=getd)
        but.pack()
        q=Button(mercurymy_frame, text="QUIT",command=mercury.destroy)
        q.grid(row=0,column=2)


    mercurymy_button=Button(space,text="MERCURY",command=mercury1,bg="#195267",fg="#F0BE25")
    mercurymy_button.place(rely = 0.173,relx=0.242)

    def venus1():
        global venus
        venus = Toplevel(space)
        venus.title("VENUS")
        venus.geometry("300x400")
        venus.config(bg="#0F0860")

        global venusme
        global venusme2
        venuspop_label=Label(venus,text="Unlike the other planets \nin our solar syst\nem, Venus spins clockwise \non its axis...", font=("helvetica",12)).pack()
        venusmy_frame= Frame(venus,bg="#0F0860")
        venusmy_frame.pack(pady=5)
        venusmep=Image.open(r"D:\spaceverse\venus.jpg")
        venusmep=venusmep.resize((100,100),Image.ANTIALIAS)
        venusme=ImageTk.PhotoImage(venusmep)
        venusmep1=Image.open(r"D:\spaceverse\V_anusqr.png")
        venusmep1=venusmep1.resize((100,100),Image.ANTIALIAS)
        venusme2=ImageTk.PhotoImage(venusmep1)
        venusl=Label(venusmy_frame,image=venusme)
        venusl.grid(row=0,column=0,padx=10)
        venusqr=Label(venusmy_frame,image=venusme2)
        venusqr.grid(row=1,column=0,padx=10)

        venusme_pic=Label(venusmy_frame,image=venusme)
        venusme_pic.grid(row=0,column=0,padx=10)
        venusme1_pic=Label(venusmy_frame,image=venusme2)
        venusme1_pic.grid(row=1,column=0,padx=10)
        dlab=Label(venus,text="To find your weight\n on venus\n write your weight bellow \n and find out:",bg="#0F0860",fg="white")
        dlab.pack()
        en=Entry(venus)
        en.pack()
        def getd():
            a=int(en.get())
            wt="your weight on venus is"+str(a*0.91)+"Kg"
            ml=Label(venus,text=wt,bg="#0F0860",fg="white")
            ml.pack()
        but=Button(venus,text="CALCULATE WEIGHT",command=getd)
        but.pack()
        q=Button(venusmy_frame, text="QUIT",command=venus.destroy)
        q.grid(row=0,column=2)


    venusmy_button=Button(space,text="VENUS",command=venus1,bg="#195267",fg="#F0BE25",width=6)
    venusmy_button.place(rely = 0.69,relx=0.3165)

    def earth1():
        global earth
        earth = Toplevel(space)
        earth.title("OUR EARTH")
        earth.geometry("300x400")
        earth.config(bg="#0F0860")

        global me
        global me2
        pop_label=Label(earth,text="Earth is the third planet from the Sun \n and the only astronomical \n object known to harbour and support life...",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        my_frame= Frame(earth,bg="#0F0860")
        my_frame.pack(pady=5)
        mep=Image.open(r"D:\spaceverse\earth.jpg")
        mep=mep.resize((100,100),Image.ANTIALIAS)
        me=ImageTk.PhotoImage(mep)
        mep1=Image.open(r"D:\spaceverse\earthqe.jpg")
        mep1=mep1.resize((100,100),Image.ANTIALIAS)
        me2=ImageTk.PhotoImage(mep1)
        earthl=Label(my_frame,image=me)
        earthl.grid(row=0,column=0,padx=10)
        earthqr=Label(my_frame,image=me2)
        earthqr.grid(row=1,column=0,padx=10)

        me_pic=Label(my_frame,image=me)
        me_pic.grid(row=0,column=0,padx=10)
        me1_pic=Label(my_frame,image=me2)

        dlab=Label(earth,text="Your weight\n on different planets\n would change\n however it will remain same \n on earth",bg="#0F0860",fg="white")
        dlab.pack()
        me1_pic.grid(row=1,column=0,padx=10)
        q=Button(my_frame, text="QUIT",command=earth.destroy)
        q.grid(row=0,column=2)

    my_button=Button(space,text="EARTH",command=earth1,bg="#195267",fg="#F0BE25",width=6)
    my_button.place(rely = 0.29,relx=0.41)



    def moon1():
        global moon
        moon = Toplevel(space)
        moon.title("MOON")
        moon.geometry("300x400")
        moon.config(bg="#0F0860")

        global moonme
        global moonme2
        moonpop_label=Label(moon,text="moon is Earths only natural satellite",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        moonmy_frame= Frame(moon,bg="#0F0860")
        moonmy_frame.pack(pady=5)
        moonmep=Image.open(r"D:\spaceverse\moon.jpg")
        moonmep=moonmep.resize((100,100),Image.ANTIALIAS)
        moonme=ImageTk.PhotoImage(moonmep)
        moonmep1=Image.open(r"D:\spaceverse\mer_curryqr.png")
        moonmep1=moonmep1.resize((100,100),Image.ANTIALIAS)
        moonme2=ImageTk.PhotoImage(moonmep1)
        moonl=Label(moonmy_frame,image=moonme)
        moonl.grid(row=0,column=0,padx=10)
        moonqr=Label(moonmy_frame,image=moonme2)
        moonqr.grid(row=1,column=0,padx=10)

        moonme_pic=Label(moonmy_frame,image=moonme)
        moonme_pic.grid(row=0,column=0,padx=10)
        moonme1_pic=Label(moonmy_frame,image=moonme2)
        moonme1_pic.grid(row=1,column=0,padx=10)
        dlab=Label(moon,text="To find your weight\n on Moon\n write your weight bellow \n and find out:",bg="#0F0860",fg="white")
        dlab.pack()
        en=Entry(moon)
        en.pack()
        def getd():
            a=int(en.get())
            wt="your weight on Moon is"+str(a*0.165)+"Kg"
            ml=Label(moon,text=wt,bg="#0F0860",fg="white")
            ml.pack()
        but=Button(moon,text="CALCULATE WEIGHT",command=getd)
        but.pack()
        q=Button(moonmy_frame, text="QUIT",command=moon.destroy)
        q.grid(row=0,column=2)


    moonmy_button=Button(space,text="MOON",command=moon1,bg="#195267",fg="#F0BE25")
    moonmy_button.place(rely = 0.43,relx=0.455)

    def mars1():
        global mars
        mars = Toplevel(space)
        mars.title("MARS")
        mars.geometry("300x400")
        mars.config(bg="#0F0860")

        global marsme
        global marsme2
        marspop_label=Label(mars,text="The biggest crater \non Mars is Borealis Basin. \nIt is 5300 miles from end to end\n and covers 40% of planet’s surface.",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        marsmy_frame= Frame(mars,bg="#0F0860")
        marsmy_frame.pack(pady=5)
        marsmep=Image.open(r"D:\spaceverse\mars.jpg")
        marsmep=marsmep.resize((100,100),Image.ANTIALIAS)
        marsme=ImageTk.PhotoImage(marsmep)
        marsmep1=Image.open(r"D:\spaceverse\marsqr.png")
        marsmep1=marsmep1.resize((100,100),Image.ANTIALIAS)
        marsme2=ImageTk.PhotoImage(marsmep1)
        marsl=Label(marsmy_frame,image=marsme)
        marsl.grid(row=0,column=0,padx=10)
        marsqr=Label(marsmy_frame,image=marsme2)
        marsqr.grid(row=1,column=0,padx=10)

        marsme_pic=Label(marsmy_frame,image=marsme)
        marsme_pic.grid(row=0,column=0,padx=10)
        marsme1_pic=Label(marsmy_frame,image=marsme2)
        dlab=Label(mars,text="To find your weight\n on Mars\n write your weight bellow \n and find out:",bg="#0F0860",fg="white")
        dlab.pack()
        marsme1_pic.grid(row=1,column=0,padx=10)
        en=Entry(mars)
        en.pack()
        def getd():
            a=int(en.get())
            wt="your weight on Mars is"+str(a*0.38)+"Kg"
            ml=Label(mars,text=wt,bg="#0F0860",fg="white")
            ml.pack()
        but=Button(mars,text="CALCULATE WEIGHT",command=getd)
        but.pack()
        q=Button(marsmy_frame, text="QUIT",command=mars.destroy)
        q.grid(row=0,column=2)


    marsmy_button=Button(space,text="MARS",command=mars1,bg="#195267",fg="#F0BE25",width=4)
    marsmy_button.place(rely = 0.8,relx=0.4729)



    def jup1():
        global jup
        jup = Toplevel(space)
        jup.title("JUPITER")
        jup.geometry("300x400")
        jup.config(bg="#0F0860")

        global jupme
        global jupme2
        juppop_label=Label(jup,text="Jupiter has the\n brightest auroras\n in the solar system",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        jupmy_frame= Frame(jup,bg="#0F0860")
        jupmy_frame.pack(pady=5)
        jupmep=Image.open(r"C:/Users/Chinmayee/Desktop/Projects/spaceverse/jupiter.jpg")
        jupmep=jupmep.resize((100,100),Image.ANTIALIAS)
        jupme=ImageTk.PhotoImage(jupmep)
        jupmep1=Image.open(r"D:\spaceverse\jupyterqr.png")
        jupmep1=jupmep1.resize((100,100),Image.ANTIALIAS)
        jupme2=ImageTk.PhotoImage(jupmep1)
        jupl=Label(jupmy_frame,image=jupme)
        jupl.grid(row=0,column=0,padx=10)
        jupqr=Label(jupmy_frame,image=jupme2)
        jupqr.grid(row=1,column=0,padx=10)

        jupme_pic=Label(jupmy_frame,image=jupme)
        jupme_pic.grid(row=0,column=0,padx=10)
        jupme1_pic=Label(jupmy_frame,image=jupme2)
        jupme1_pic.grid(row=1,column=0,padx=10)
        dlab=Label(jupiter,text="To find your weight\n on JUPITER\n write your weight bellow \n and find out:",bg="#0F0860",fg="white")
        dlab.pack()
        en=Entry(jupiter)
        en.pack()
        def getd():
            a=int(en.get())
            wt="your weight on jupiter is"+str(a*2.34)+"Kg"
            ml=Label(jupiter,text=wt,bg="#0F0860",fg="white")
            ml.pack()
        but=Button(jupiter,text="CALCULATE WEIGHT",command=getd)
        but.pack()
        q=Button(jupmy_frame, text="QUIT",command=jup.destroy)
        q.grid(row=0,column=2)


    jupmy_button=Button(space,text="JUPITER",command=jup1,bg="#195267",fg="#F0BE25")
    jupmy_button.place(rely = 0.4,relx=0.56)


    def saturn1():
        global saturn
        saturn = Toplevel(space)
        saturn.title("SATURN")
        saturn.geometry("300x400")
        saturn.config(bg="#0F0860")

        global saturnme
        global saturnme2
        saturnpop_label=Label(saturn,text="Saturn goes around \nthe Sun very slowly. \nA year on Saturn is more \nthan 29 Earth years.",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        saturnmy_frame= Frame(saturn,bg="#0F0860")
        saturnmy_frame.pack(pady=5)
        saturnmep=Image.open(r"D:\spaceverse\saturn.jpg")
        saturnmep=saturnmep.resize((100,100),Image.ANTIALIAS)
        saturnme=ImageTk.PhotoImage(saturnmep)
        saturnmep1=Image.open(r"D:\spaceverse\sitting_uranusqr.png")
        saturnmep1=saturnmep1.resize((100,100),Image.ANTIALIAS)
        saturnme2=ImageTk.PhotoImage(saturnmep1)
        saturnl=Label(saturnmy_frame,image=saturnme)
        saturnl.grid(row=0,column=0,padx=10)
        saturnqr=Label(saturnmy_frame,image=saturnme2)
        saturnqr.grid(row=1,column=0,padx=10)

        saturnme_pic=Label(saturnmy_frame,image=saturnme)
        saturnme_pic.grid(row=0,column=0,padx=10)
        saturnme1_pic=Label(saturnmy_frame,image=saturnme2)
        saturnme1_pic.grid(row=1,column=0,padx=10)
        dlab=Label(saturn,text="To find your weight\n on saturn\n write your weight bellow \n and find out:",bg="#0F0860",fg="white")
        dlab.pack()
        en=Entry(saturn)
        en.pack()
        def getd():
            a=int(en.get())
            wt="your weight on saturn is"+str(a*1.06)+"Kg"
            ml=Label(saturn,text=wt,bg="#0F0860",fg="white")
            ml.pack()
        but=Button(saturn,text="CALCULATE WEIGHT",command=getd)
        but.pack()
        q=Button(saturnmy_frame, text="QUIT",command=saturn.destroy)
        q.grid(row=0,column=2)


    saturnmy_button=Button(space,text="SATURN",command=saturn1,bg="#195267",fg="#F0BE25")
    saturnmy_button.place(rely = 0.781,relx=0.675)


    def uranus1():
        global uranus
        uranus = Toplevel(space)
        uranus.title("URANUS")
        uranus.geometry("300x400")
        uranus.config(bg="#0F0860")

        global uranusme
        global uranusme2
        uranuspop_label=Label(uranus,text="Uranus was the\n first planet discovered \nin the modern age",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        uranusmy_frame= Frame(uranus,bg="#0F0860")
        uranusmy_frame.pack(pady=5)
        uranusmep=Image.open(r"D:\spaceverse\uranus.jpg")
        uranusmep=uranusmep.resize((100,100),Image.ANTIALIAS)
        uranusme=ImageTk.PhotoImage(uranusmep)
        uranusmep1=Image.open(r"D:\spaceverse\Ur_anusqr.png")
        uranusmep1=uranusmep1.resize((100,100),Image.ANTIALIAS)
        uranusme2=ImageTk.PhotoImage(uranusmep1)
        uranusl=Label(uranusmy_frame,image=uranusme)
        uranusl.grid(row=0,column=0,padx=10)
        uranusqr=Label(uranusmy_frame,image=uranusme2)
        uranusqr.grid(row=1,column=0,padx=10)

        uranusme_pic=Label(uranusmy_frame,image=uranusme)
        uranusme_pic.grid(row=0,column=0,padx=10)
        uranusme1_pic=Label(uranusmy_frame,image=uranusme2)
        uranusme1_pic.grid(row=1,column=0,padx=10)
        dlab=Label(uranus,text="To find your weight\n on URANUS\n write your weight bellow \n and find out:",bg="#0F0860",fg="white")
        dlab.pack()
        en=Entry(uranus)
        en.pack()
        def getd():
            a=int(en.get())
            wt="your weight on uranus is"+str(a*0.92)+"Kg"
            ml=Label(uranus,text=wt,bg="#0F0860",fg="white")
            ml.pack()
        but=Button(unanus,text="CALCUATE WEIGHT",command=getd)
        but.pack()
        q=Button(uranusmy_frame, text="quit",command=uranus.destroy)
        q.grid(row=0,column=2)


    uranusmy_button=Button(space,text="URANUS",command=uranus1,bg="#195267",fg="#F0BE25")
    uranusmy_button.place(rely = 0.53,relx=0.776)


    def neptune1():
        global neptune
        neptune = Toplevel(space)
        neptune.title("NEPTUNE")
        neptune.geometry("300x400")
        neptune.config(bg="#0F0860")

        global neptuneme
        global neptuneme2
        neptunepop_label=Label(neptune,text="Because of dwarf \nplanet Pluto’s elliptical orbit,\n Pluto is sometimes\n closer to the Sun \n(and us) than\n Neptune is...",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        neptunemy_frame= Frame(neptune,bg="#0F0860")
        neptunemy_frame.pack(pady=5)
        neptunemep=Image.open(r"D:\spaceverse\neptune.jpg")
        neptunemep=neptunemep.resize((100,100),Image.ANTIALIAS)
        neptuneme=ImageTk.PhotoImage(neptunemep)
        neptunemep1=Image.open(r"D:\spaceverse\Neptoonqr.png")
        neptunemep1=neptunemep1.resize((100,100),Image.ANTIALIAS)
        neptuneme2=ImageTk.PhotoImage(neptunemep1)
        neptunel=Label(neptunemy_frame,image=neptuneme)
        neptunel.grid(row=0,column=0,padx=10)
        neptuneqr=Label(neptunemy_frame,image=neptuneme2)
        neptuneqr.grid(row=1,column=0,padx=10)

        neptuneme_pic=Label(neptunemy_frame,image=neptuneme)
        neptuneme_pic.grid(row=0,column=0,padx=10)
        neptuneme1_pic=Label(neptunemy_frame,image=neptuneme2)
        neptuneme1_pic.grid(row=1,column=0,padx=10)
        dlab=Label(neptune,text="To find your weight\n on Neptune\n write your weight bellow \n and find out:",bg="#0F0860",fg="white")
        dlab.pack()
        en=Entry(neptune)
        en.pack()
        def getd():
            a=int(en.get())
            wt="your weight is"+str(a*1.19)+"Kg"
            ml=Label(neptune,text=wt,bg="#0F0860",fg="white")
            ml.pack()
        but=Button(neptune,text="CALCULATE WEIGHT",command=getd)
        but.pack()
        q=Button(neptunemy_frame, text="QUIT",command=neptune.destroy)
        q.grid(row=0,column=2)


    neptunemy_button=Button(space,text="NEPTUNE",command=neptune1,bg="#195267",fg="#F0BE25")
    neptunemy_button.place(rely = 0.93,relx=0.892)

    def comet1():
        global comet
        comet = Toplevel(space)
        comet.title("COMET")
        comet.geometry("300x300")
        comet.config(bg="#0F0860")

        global cometme
        global cometme2
        cometpop_label=Label(comet,text="The most famous comet is\n Halley’s Comet. \nIt has been observed \nsince at least 240 B.C.\n It was named after \nthe British astronomer \nEdmond Halley",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        cometmy_frame= Frame(comet,bg="#0F0860")
        cometmy_frame.pack(pady=5)
        cometmep=Image.open(r"D:\spaceverse\paper.jpg")
        cometmep=cometmep.resize((100,100),Image.ANTIALIAS)
        cometme=ImageTk.PhotoImage(cometmep)
        cometmep1=Image.open(r"D:\spaceverse\paper.jpg")
        cometmep1=cometmep1.resize((100,100),Image.ANTIALIAS)
        cometme2=ImageTk.PhotoImage(cometmep1)
        cometl=Label(cometmy_frame,image=cometme)
        cometl.grid(row=0,column=0,padx=10)
        cometqr=Label(cometmy_frame,image=cometme2)
        cometqr.grid(row=1,column=0,padx=10)

        cometme_pic=Label(cometmy_frame,image=cometme)
        cometme_pic.grid(row=0,column=0,padx=10)
        cometme1_pic=Label(cometmy_frame,image=cometme2)
        cometme1_pic.grid(row=1,column=0,padx=10)
        q=Button(cometmy_frame, text="QUIT",command=comet.destroy)
        q.grid(row=0,column=2)


    cometmy_button=Button(space,text="COMET",command=comet1,bg="#195267",fg="#F0BE25")
    cometmy_button.place(rely = 0.8,relx=0.1)
    def asteroid1():
        global asteroid
        asteroid = Toplevel(space)
        asteroid.title("ASTEROID BELT")
        asteroid.geometry("300x300")
        asteroid.config(bg="#0F0860")

        global asteroidme
        global asteroidme2
        asteroidpop_label=Label(asteroid,text="The asteroid 1/Ceres\n is also designated as a dwarf planet\n, the largest one\n in the inner solar system\n, lies in the asteroid belt",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        asteroidmy_frame= Frame(asteroid,bg="#0F0860")
        asteroidmy_frame.pack(pady=5)
        asteroidmep=Image.open(r"D:\spaceverse\rock.jpg")
        asteroidmep=asteroidmep.resize((100,100),Image.ANTIALIAS)
        asteroidme=ImageTk.PhotoImage(asteroidmep)
        asteroidmep1=Image.open(r"D:\spaceverse\rock.jpg")
        asteroidmep1=asteroidmep1.resize((100,100),Image.ANTIALIAS)
        asteroidme2=ImageTk.PhotoImage(asteroidmep1)
        asteroidl=Label(asteroidmy_frame,image=asteroidme)
        asteroidl.grid(row=0,column=0,padx=10)
        asteroidqr=Label(asteroidmy_frame,image=asteroidme2)
        asteroidqr.grid(row=1,column=0,padx=10)

        asteroidme_pic=Label(asteroidmy_frame,image=asteroidme)
        asteroidme_pic.grid(row=0,column=0,padx=10)
        asteroidme1_pic=Label(asteroidmy_frame,image=asteroidme2)
        asteroidme1_pic.grid(row=1,column=0,padx=10)
        q=Button(asteroidmy_frame, text="quit",command=asteroid.destroy)
        q.grid(row=0,column=2)


    asteroidmy_button=Button(space,text="ASTEROID  BELT",command=asteroid1,bg="#195267",fg="#F0BE25")
    asteroidmy_button.place(rely = 0.1,relx=0.5)
    Exi=Button(space,text="<---Go Back To Tardis",command=tardsp ,bg="#195267",fg="#F0BE25")
    Exi.place(rely =0.05,relx=0.03)
    ef=Button(space,text="End The Journey--->",command=exispa ,bg="#195267",fg="#F0BE25")
    ef.place(rely =0.05,relx=0.88)
    space.mainloop()
# space1()

def sat1():
    global sat
    sat=Tk()
    sat.title("SATELLITES")
    sat.geometry("450x350")
    main_frame = Frame(sat,bg="#202F4D")
    main_frame.pack(fill=BOTH, expand=1)
    my_canvas = Canvas(main_frame,bg="#202F4D")
    my_canvas.pack(side=LEFT, fill=BOTH, expand=1)
    my_scrollbar = ttk.Scrollbar(main_frame, orient=VERTICAL, command=my_canvas.yview)
    my_scrollbar.pack(side=RIGHT, fill=Y)
    my_canvas.configure(yscrollcommand=my_scrollbar.set)
    my_canvas.bind('<Configure>', lambda e: my_canvas.configure(scrollregion = my_canvas.bbox("all")))
    Sframe = Frame(my_canvas,bg="#202F4D",height=500,width=500)
    my_canvas.create_window((0,0), window=Sframe, anchor="nw")
    labels=Label(Sframe,text="“One small step for Satellite,\n is one giant leap for Science”\n Read all the amazing adventures\n of previous satellites.... ",fg="#F0BE25",bg="#202F4D",font=("helvetica 14"))
    labels.grid(column=0,row=1,padx=70,pady=20,sticky="nw")


    trackmep=Image.open(r"D:\spaceverse\orb.png")
    trackmep=trackmep.resize((100,100),Image.ANTIALIAS)
    trackme=ImageTk.PhotoImage(trackmep)
    trackme_pic=Label(Sframe,image=trackme)
    trackme_pic.grid(column=0,row=2,padx=100,pady=20,sticky="nw")

    labels=Label(Sframe,text="Scan the QR\n code for \n live satellite \n positioning ",fg="#F0BE25",bg="#202F4D",font="2")
    labels.grid(column=0,row=2,padx=220,pady=30,sticky="nw")


    def pioneer1():
        global pioneer
        pioneer = Toplevel(sat)
        pioneer.title("pioneer")
        pioneer.geometry("300x300")
        pioneer.config(bg="#0F0860")

        global pioneerme
        global pioneerme2
        pioneerpop_label=Label(pioneer,text="Pioneer 10 is an American space probe,\n launched in 1972 and weighing 258 kilograms,\n that completed the first mission to the planet Jupiter.\n Thereafter, Pioneer 10 became the first of five artificial objects\n to achieve the escape velocity needed to leave the Solar System.",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        pioneermy_frame= Frame(pioneer,bg="#0F0860")
        pioneermy_frame.pack(pady=5)
        pioneermep=Image.open(r"D:\spaceverse\pioneer.jpg")
        pioneermep=pioneermep.resize((100,100),Image.ANTIALIAS)
        pioneerme=ImageTk.PhotoImage(pioneermep)
        pioneermep1=Image.open(r"D:\spaceverse\pioneerqr.png")
        pioneermep1=pioneermep1.resize((100,100),Image.ANTIALIAS)
        pioneerme2=ImageTk.PhotoImage(pioneermep1)
        pioneerl=Label(pioneermy_frame,image=pioneerme)
        pioneerl.grid(row=0,column=0,padx=10)
        pioneerqr=Label(pioneermy_frame,image=pioneerme2)
        pioneerqr.grid(row=1,column=0,padx=10)

        pioneerme_pic=Label(pioneermy_frame,image=pioneerme)
        pioneerme_pic.grid(row=0,column=0,padx=10)
        pioneerme1_pic=Label(pioneermy_frame,image=pioneerme2)
        pioneerme1_pic.grid(row=1,column=0,padx=10)
        q=Button(pioneermy_frame, text="quit",command=pioneer.destroy)
        q.grid(row=0,column=2)

    pioneermy_button=Button(Sframe,text="PIONEER",command=pioneer1,bg="black",fg="#25B7F0",height=1,width=17)
    pioneermy_button.grid(column=0,row=3,sticky="nw",padx=30,pady=30,ipadx=20,ipady=10)

    def hbusa1():
        global hbusa
        hbusa = Toplevel(sat)
        hbusa.title("hayabusa")
        hbusa.geometry("300x300")
        hbusa.config(bg="#0F0860")

        global hbusame
        global hbusame2
        hbusapop_label=Label(hbusa,text="Hayabusa was a robotic spacecraft developed by \n the Japan Aerospace Exploration Agency (JAXA) \n to return a sample of material from a small near-Earth asteroid \n named 25143 Itokawa to Earth for further analysis.",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        hbusamy_frame= Frame(hbusa,bg="#0F0860")
        hbusamy_frame.pack(pady=5)
        hbusamep=Image.open(r"D:\spaceverse\hayabusa.jpg")
        hbusamep=hbusamep.resize((100,100),Image.ANTIALIAS)
        hbusame=ImageTk.PhotoImage(hbusamep)
        hbusamep1=Image.open(r"D:\spaceverse\hbusaqr.png")
        hbusamep1=hbusamep1.resize((100,100),Image.ANTIALIAS)
        hbusame2=ImageTk.PhotoImage(hbusamep1)
        hbusal=Label(hbusamy_frame,image=hbusame)
        hbusal.grid(row=0,column=0,padx=10)
        hbusaqr=Label(hbusamy_frame,image=hbusame2)
        hbusaqr.grid(row=1,column=0,padx=10)

        hbusame_pic=Label(hbusamy_frame,image=hbusame)
        hbusame_pic.grid(row=0,column=0,padx=10)
        hbusame1_pic=Label(hbusamy_frame,image=hbusame2)
        hbusame1_pic.grid(row=1,column=0,padx=10)
        q=Button(hbusamy_frame, text="quit",command=hbusa.destroy)
        q.grid(row=0,column=2)


    hbusamy_button=Button(Sframe,text="HAYABUSA",command=hbusa1,bg="black",fg="#25B7F0",height=1,width=17)
    hbusamy_button.grid(column=0,row=3,sticky="nw",padx=230,pady=30,ipadx=20,ipady=10)



    def horizon1():
        global horizon
        horizon = Toplevel(sat)
        horizon.title("horizon")
        horizon.geometry("300x300")
        horizon.config(bg="#0F0860")

        global horizonme
        global horizonme2
        horizonpop_label=Label(horizon,text="NASA's New Horizons spacecraft \n is the first spacecraft to explore Pluto up close,\n flying by the dwarf planet and its moons on July 14, 2015.\n In early 2019, New Horizons flew past its second major science target—2014 MU69,\n the most distant object ever explored up close.",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        horizonmy_frame= Frame(horizon,bg="#0F0860")
        horizonmy_frame.pack(pady=5)
        horizonmep=Image.open(r"D:\spaceverse\new horizons.jpg")
        horizonmep=horizonmep.resize((100,100),Image.ANTIALIAS)
        horizonme=ImageTk.PhotoImage(horizonmep)
        horizonmep1=Image.open(r"D:\spaceverse\newhqr.png")
        horizonmep1=horizonmep1.resize((100,100),Image.ANTIALIAS)
        horizonme2=ImageTk.PhotoImage(horizonmep1)
        horizonl=Label(horizonmy_frame,image=horizonme)
        horizonl.grid(row=0,column=0,padx=10)
        horizonqr=Label(horizonmy_frame,image=horizonme2)
        horizonqr.grid(row=1,column=0,padx=10)

        horizonme_pic=Label(horizonmy_frame,image=horizonme)
        horizonme_pic.grid(row=0,column=0,padx=10)
        horizonme1_pic=Label(horizonmy_frame,image=horizonme2)
        horizonme1_pic.grid(row=1,column=0,padx=10)
        q=Button(horizonmy_frame, text="quit",command=horizon.destroy)
        q.grid(row=0,column=2)


    horizonmy_button=Button(Sframe,text="NEW HORIZONS",command=horizon1,bg="black",fg="#25B7F0",height=1,width=17)
    horizonmy_button.grid(column=0,row=4,sticky="nw",padx=30,pady=30,ipadx=20,ipady=10)



    def voyager1():
        global voyager
        voyager = Toplevel(sat)
        voyager.title("voyager")
        voyager.geometry("300x300")
        voyager.config(bg="#0F0860")

        global voyagerme
        global voyagerme2
        voyagerpop_label=Label(voyager,text="No spacecraft has gone farther than Voyager 1.\n  The spacecraft is currently exploring a transitional zone \n between our solar system and interstellar space. \n Voyager 1 and 2 were designed to take advantage of a rare planetary alignment \n to explore the outer solar system.\n Voyager 1 targeted Jupiter and Saturn before continuing \n on to chart the far edges of our solar system.",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        voyagermy_frame= Frame(voyager,bg="#0F0860")
        voyagermy_frame.pack(pady=5)
        voyagermep=Image.open(r"D:\spaceverse\voyager.jpg")
        voyagermep=voyagermep.resize((100,100),Image.ANTIALIAS)
        voyagerme=ImageTk.PhotoImage(voyagermep)
        voyagermep1=Image.open(r"D:\spaceverse\voyagerqr.png")
        voyagermep1=voyagermep1.resize((100,100),Image.ANTIALIAS)
        voyagerme2=ImageTk.PhotoImage(voyagermep1)
        voyagerl=Label(voyagermy_frame,image=voyagerme)
        voyagerl.grid(row=0,column=0,padx=10)
        voyagerqr=Label(voyagermy_frame,image=voyagerme2)
        voyagerqr.grid(row=1,column=0,padx=10)

        voyagerme_pic=Label(voyagermy_frame,image=voyagerme)
        voyagerme_pic.grid(row=0,column=0,padx=10)
        voyagerme1_pic=Label(voyagermy_frame,image=voyagerme2)
        voyagerme1_pic.grid(row=1,column=0,padx=10)
        q=Button(voyagermy_frame, text="quit",command=voyager.destroy)
        q.grid(row=0,column=2)


    voyagermy_button=Button(Sframe,text="VOYAGERS",command=voyager1,bg="black",fg="#25B7F0",height=1,width=17)
    voyagermy_button.grid(column=0,row=4,sticky="nw",padx=230,pady=30,ipadx=20,ipady=10, )



    def galileo1():
        global galileo
        galileo = Toplevel(sat)
        galileo.title("galileo")
        galileo.geometry("300x300")
        galileo.config(bg="#0F0860")

        global galileome
        global galileome2
        galileopop_label=Label(galileo,text="Galileo is a global navigation satellite system (GNSS) \n that went live in 2016, created by the European Union \n through the European Space Agency (ESA),\n operated by the European Union Agency \n for the Space Programme (EUSPA)",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        galileomy_frame= Frame(galileo,bg="#0F0860")
        galileomy_frame.pack(pady=5)
        galileomep=Image.open(r"D:\spaceverse\galelio.jpg")
        galileomep=galileomep.resize((100,100),Image.ANTIALIAS)
        galileome=ImageTk.PhotoImage(galileomep)
        galileomep1=Image.open(r"D:\spaceverse\Galileoqr.png")
        galileomep1=galileomep1.resize((100,100),Image.ANTIALIAS)
        galileome2=ImageTk.PhotoImage(galileomep1)
        galileol=Label(galileomy_frame,image=galileome)
        galileol.grid(row=0,column=0,padx=10)
        galileoqr=Label(galileomy_frame,image=galileome2)
        galileoqr.grid(row=1,column=0,padx=10)

        galileome_pic=Label(galileomy_frame,image=galileome)
        galileome_pic.grid(row=0,column=0,padx=10)
        galileome1_pic=Label(galileomy_frame,image=galileome2)
        galileome1_pic.grid(row=1,column=0,padx=10)
        q=Button(galileomy_frame, text="quit",command=galileo.destroy)
        q.grid(row=0,column=2)


    galileomy_button=Button(Sframe,text="GALILEO",command=galileo1,bg="black",fg="#25B7F0",height=1,width=17)
    galileomy_button.grid(column=0,row=5,sticky="nw",padx=30,pady=30,ipadx=20,ipady=10)




    def apollo1():
        global apollo
        apollo = Toplevel(sat)
        apollo.title("apollo")
        apollo.geometry("300x300")
        apollo.config(bg="#0F0860")

        global apollome
        global apollome2
        apollopop_label=Label(apollo,text="The spacecraft's main objectives were to study the plasma,\n particle and magnetic-field environment of the \n Moon and map the lunar gravity field.",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        apollomy_frame= Frame(apollo,bg="#0F0860")
        apollomy_frame.pack(pady=5)
        apollomep=Image.open(r"D:\spaceverse\apollo11 lunar.jpg")
        apollomep=apollomep.resize((100,100),Image.ANTIALIAS)
        apollome=ImageTk.PhotoImage(apollomep)
        apollomep1=Image.open(r"D:\spaceverse\apollo.png")
        apollomep1=apollomep1.resize((100,100),Image.ANTIALIAS)
        apollome2=ImageTk.PhotoImage(apollomep1)
        apollol=Label(apollomy_frame,image=apollome)
        apollol.grid(row=0,column=0,padx=10)
        apolloqr=Label(apollomy_frame,image=apollome2)
        apolloqr.grid(row=1,column=0,padx=10)

        apollome_pic=Label(apollomy_frame,image=apollome)
        apollome_pic.grid(row=0,column=0,padx=10)
        apollome1_pic=Label(apollomy_frame,image=apollome2)
        apollome1_pic.grid(row=1,column=0,padx=10)
        q=Button(apollomy_frame, text="quit",command=apollo.destroy)
        q.grid(row=0,column=2)

    apollomy_button=Button(Sframe,text="APOLLO 11",command=apollo1,bg="black",fg="#25B7F0",height=1,width=17)
    apollomy_button.grid(column=0,row=5,sticky="nw",padx=230,pady=30,ipadx=20,ipady=10)

    def parker1():
        global parker
        parker = Toplevel(sat)
        parker.title("parker")
        parker.geometry("300x300")
        parker.config(bg="#0F0860")

        global parkerme
        global parkerme2
        parkerpop_label=Label(parker,text="The Parker Solar Probe is a NASA space probe launched in 2018 \n with the mission of making observations of the outer corona of the Sun.\n It will approach to within 9.86 solar radii from the center of the Sun,\n  and by 2025 will travel, at closest approach, as fast as 690,000 km/h,\n or 0.064% the speed of light.",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        parkermy_frame= Frame(parker,bg="#0F0860")
        parkermy_frame.pack(pady=5)
        parkermep=Image.open(r"D:\spaceverse\parker.png")
        parkermep=parkermep.resize((100,100),Image.ANTIALIAS)
        parkerme=ImageTk.PhotoImage(parkermep)
        parkermep1=Image.open(r"D:\spaceverse\parkerqr.png")
        parkermep1=parkermep1.resize((100,100),Image.ANTIALIAS)
        parkerme2=ImageTk.PhotoImage(parkermep1)
        parkerl=Label(parkermy_frame,image=parkerme)
        parkerl.grid(row=0,column=0,padx=10)
        parkerqr=Label(parkermy_frame,image=parkerme2)
        parkerqr.grid(row=1,column=0,padx=10)

        parkerme_pic=Label(parkermy_frame,image=parkerme)
        parkerme_pic.grid(row=0,column=0,padx=10)
        parkerme1_pic=Label(parkermy_frame,image=parkerme2)
        parkerme1_pic.grid(row=1,column=0,padx=10)
        q=Button(parkermy_frame, text="quit",command=parker.destroy)
        q.grid(row=0,column=2)


    parkermy_button=Button(Sframe,text="PARKER SOLAR PROBE",command=parker1,bg="black",fg="#25B7F0",height=1,width=17)
    parkermy_button.grid(column=0,row=6,sticky="nw",padx=30,pady=30,ipadx=20,ipady=10)

    def cassini1():
        global cassini
        cassini = Toplevel(sat)
        cassini.title("cassini")
        cassini.geometry("300x300")
        cassini.config(bg="#0F0860")

        global cassinime
        global cassinime2
        cassinipop_label=Label(cassini,text="For more than a decade, NASA’s Cassini spacecraft \n shared the wonders of Saturn and its family of icy moons—taking us \n to astounding worlds where methane rivers run to a methane sea \n and where jets of ice and gas are blasting material \n into space from a liquid water ocean that might harbor \n the ingredients for life.",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        cassinimy_frame= Frame(cassini,bg="#0F0860")
        cassinimy_frame.pack(pady=5)
        cassinimep=Image.open(r"D:\spaceverse\cassini.jpg")
        cassinimep=cassinimep.resize((100,100),Image.ANTIALIAS)
        cassinime=ImageTk.PhotoImage(cassinimep)
        cassinimep1=Image.open(r"D:\spaceverse\cassiniqr.png")
        cassinimep1=cassinimep1.resize((100,100),Image.ANTIALIAS)
        cassinime2=ImageTk.PhotoImage(cassinimep1)
        cassinil=Label(cassinimy_frame,image=cassinime)
        cassinil.grid(row=0,column=0,padx=10)
        cassiniqr=Label(cassinimy_frame,image=cassinime2)
        cassiniqr.grid(row=1,column=0,padx=10)

        cassinime_pic=Label(cassinimy_frame,image=cassinime)
        cassinime_pic.grid(row=0,column=0,padx=10)
        cassinime1_pic=Label(cassinimy_frame,image=cassinime2)
        cassinime1_pic.grid(row=1,column=0,padx=10)
        q=Button(cassinimy_frame, text="quit",command=cassini.destroy)
        q.grid(row=0,column=2)

    cassinimy_button=Button(Sframe,text="CASSINI",command=cassini1,bg="black",fg="#25B7F0",height=1,width=17)
    cassinimy_button.grid(column=0,row=6,sticky="nw",padx=230,pady=30,ipadx=20,ipady=10)

    def ISS1():
        global ISS
        ISS = Toplevel(sat)
        ISS.title("ISS")
        ISS.geometry("300x300")
        ISS.config(bg="#0F0860")

        global ISSme
        global ISSme2
        ISSpop_label=Label(ISS,text="The International Space Station \n is a modular space station in low Earth orbit.\n It is a multinational collaborative project \n involving five participating space agencies: \n NASA, Roscosmos, JAXA, ESA, and CSA",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        ISSmy_frame= Frame(ISS,bg="#0F0860")
        ISSmy_frame.pack(pady=5)
        ISSmep=Image.open(r"D:\spaceverse\ISS.jpg")
        ISSmep=ISSmep.resize((100,100),Image.ANTIALIAS)
        ISSme=ImageTk.PhotoImage(ISSmep)
        ISSmep1=Image.open(r"D:\spaceverse\issqr.png")
        ISSmep1=ISSmep1.resize((100,100),Image.ANTIALIAS)
        ISSme2=ImageTk.PhotoImage(ISSmep1)
        ISSl=Label(ISSmy_frame,image=ISSme)
        ISSl.grid(row=0,column=0,padx=10)
        ISSqr=Label(ISSmy_frame,image=ISSme2)
        ISSqr.grid(row=1,column=0,padx=10)

        ISSme_pic=Label(ISSmy_frame,image=ISSme)
        ISSme_pic.grid(row=0,column=0,padx=10)
        ISSme1_pic=Label(ISSmy_frame,image=ISSme2)
        ISSme1_pic.grid(row=1,column=0,padx=10)
        q=Button(ISSmy_frame, text="quit",command=ISS.destroy)
        q.grid(row=0,column=2)


    ISSmy_button=Button(Sframe,text="ISS",command=ISS1,bg="black",fg="#25B7F0",height=1,width=17)
    ISSmy_button.grid(column=0,row=7,sticky="nw",padx=30,pady=30,ipadx=20,ipady=10)

    def hubble1():
        global hubble
        hubble = Toplevel(sat)
        hubble.title("hubble")
        hubble.geometry("300x300")
        hubble.config(bg="#0F0860")

        global hubbleme
        global hubbleme2
        hubblepop_label=Label(hubble,text="The Hubble Space Telescope is a space telescope \n that was launched into low Earth orbit in 1990 \n and remains in operation. It was not the first space telescope,\n but it is one of the largest and most versatile,\n renowned both as a vital research tool \n and as a public relations boon for astronomy. ",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        hubblemy_frame= Frame(hubble,bg="#0F0860")
        hubblemy_frame.pack(pady=5)
        hubblemep=Image.open(r"D:\spaceverse\HUBBLE.jpg")
        hubblemep=hubblemep.resize((100,100),Image.ANTIALIAS)
        hubbleme=ImageTk.PhotoImage(hubblemep)
        hubblemep1=Image.open(r"D:\spaceverse\hubbleqr.png")
        hubblemep1=hubblemep1.resize((100,100),Image.ANTIALIAS)
        hubbleme2=ImageTk.PhotoImage(hubblemep1)
        hubblel=Label(hubblemy_frame,image=hubbleme)
        hubblel.grid(row=0,column=0,padx=10)
        hubbleqr=Label(hubblemy_frame,image=hubbleme2)
        hubbleqr.grid(row=1,column=0,padx=10)

        hubbleme_pic=Label(hubblemy_frame,image=hubbleme)
        hubbleme_pic.grid(row=0,column=0,padx=10)
        hubbleme1_pic=Label(hubblemy_frame,image=hubbleme2)
        hubbleme1_pic.grid(row=1,column=0,padx=10)
        q=Button(hubblemy_frame, text="quit",command=hubble.destroy)
        q.grid(row=0,column=2)


    hubblemy_button=Button(Sframe,text="HUBBLE",command=hubble1,bg="black",fg="#25B7F0",height=1,width=17)
    hubblemy_button.grid(column=0,row=7,sticky="nw",padx=230,pady=30,ipadx=20,ipady=10)

    def kepplar1():
        global kepplar
        kepplar = Toplevel(sat)
        kepplar.title("kepplar")
        kepplar.geometry("300x300")
        kepplar.config(bg="#0F0860")

        global kepplarme
        global kepplarme2
        kepplarpop_label=Label(kepplar,text="The Kepler space telescope is a retired space telescope \n launched by NASA in 2009 to discover Earth-size planets \n orbiting other stars. the spacecraft \n was launched into an Earth-trailing heliocentric orbit.",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        kepplarmy_frame= Frame(kepplar,bg="#0F0860")
        kepplarmy_frame.pack(pady=5)
        kepplarmep=Image.open(r"D:\spaceverse\Kepler-NASA.jpg")
        kepplarmep=kepplarmep.resize((100,100),Image.ANTIALIAS)
        kepplarme=ImageTk.PhotoImage(kepplarmep)
        kepplarmep1=Image.open(r"D:\spaceverse\keplerqr.png")
        kepplarmep1=kepplarmep1.resize((100,100),Image.ANTIALIAS)
        kepplarme2=ImageTk.PhotoImage(kepplarmep1)
        kepplarl=Label(kepplarmy_frame,image=kepplarme)
        kepplarl.grid(row=0,column=0,padx=10)
        kepplarqr=Label(kepplarmy_frame,image=kepplarme2)
        kepplarqr.grid(row=1,column=0,padx=10)

        kepplarme_pic=Label(kepplarmy_frame,image=kepplarme)
        kepplarme_pic.grid(row=0,column=0,padx=10)
        kepplarme1_pic=Label(kepplarmy_frame,image=kepplarme2)
        kepplarme1_pic.grid(row=1,column=0,padx=10)
        q=Button(kepplarmy_frame, text="quit",command=kepplar.destroy)
        q.grid(row=0,column=2)


    kepplarmy_button=Button(Sframe,text="KEPLER",command=kepplar1,bg="black",fg="#25B7F0",height=1,width=17)
    kepplarmy_button.grid(column=0,row=8,sticky="nw",padx=30,pady=30,ipadx=20,ipady=10)

    def GPS1():
        global GPS
        GPS = Toplevel(sat)
        GPS.title("GPS")
        GPS.geometry("300x300")
        GPS.config(bg="#0F0860")

        global GPSme
        global GPSme2
        GPSpop_label=Label(GPS,text="GPS satellite blocks are the various \n production generations of the Global Positioning System (GPS) \n used for satellite navigation. \n The first satellite in the system, Navstar 1,\n was launched on 22 February 1978.",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        GPSmy_frame= Frame(GPS,bg="#0F0860")
        GPSmy_frame.pack(pady=5)
        GPSmep=Image.open(r"D:\spaceverse\GPS IIR.jpg")
        GPSmep=GPSmep.resize((100,100),Image.ANTIALIAS)
        GPSme=ImageTk.PhotoImage(GPSmep)
        GPSmep1=Image.open(r"D:\spaceverse\gps1qr.png")
        GPSmep1=GPSmep1.resize((100,100),Image.ANTIALIAS)
        GPSme2=ImageTk.PhotoImage(GPSmep1)
        GPSl=Label(GPSmy_frame,image=GPSme)
        GPSl.grid(row=0,column=0,padx=10)
        GPSqr=Label(GPSmy_frame,image=GPSme2)
        GPSqr.grid(row=1,column=0,padx=10)

        GPSme_pic=Label(GPSmy_frame,image=GPSme)
        GPSme_pic.grid(row=0,column=0,padx=10)
        GPSme1_pic=Label(GPSmy_frame,image=GPSme2)
        GPSme1_pic.grid(row=1,column=0,padx=10)
        q=Button(GPSmy_frame, text="quit",command=GPS.destroy)
        q.grid(row=0,column=2)


    GPSmy_button=Button(Sframe,text="GPS",command=GPS1,bg="black",fg="#25B7F0",height=1,width=17)
    GPSmy_button.grid(column=0,row=8,sticky="nw",padx=230,pady=30,ipadx=20,ipady=10)

    def terra1():
        global terra
        terra = Toplevel(sat)
        terra.title("terra")
        terra.geometry("300x300")
        terra.config(bg="#0F0860")

        global terrame
        global terrame2
        terrapop_label=Label(terra,text="Terra (EOS AM-1) is a multi-national, NASA scientific research \n satellite in a Sun-synchronous orbit around \n the Earth that takes simultaneous measurements \n of Earth’s atmosphere, land, and water to understand \n how Earth is changing and to identify the consequences \n for life on Earth. ",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        terramy_frame= Frame(terra,bg="#0F0860")
        terramy_frame.pack(pady=5)
        terramep=Image.open(r"D:\spaceverse\terra.jpg")
        terramep=terramep.resize((100,100),Image.ANTIALIAS)
        terrame=ImageTk.PhotoImage(terramep)
        terramep1=Image.open(r"D:\spaceverse\terraqr.png")
        terramep1=terramep1.resize((100,100),Image.ANTIALIAS)
        terrame2=ImageTk.PhotoImage(terramep1)
        terral=Label(terramy_frame,image=terrame)
        terral.grid(row=0,column=0,padx=10)
        terraqr=Label(terramy_frame,image=terrame2)
        terraqr.grid(row=1,column=0,padx=10)

        terrame_pic=Label(terramy_frame,image=terrame)
        terrame_pic.grid(row=0,column=0,padx=10)
        terrame1_pic=Label(terramy_frame,image=terrame2)
        terrame1_pic.grid(row=1,column=0,padx=10)
        q=Button(terramy_frame, text="quit",command=terra.destroy)
        q.grid(row=0,column=2)

    terramy_button=Button(Sframe,text="TERRA",command=terra1,bg="black",fg="#25B7F0",height=1,width=17)
    terramy_button.grid(column=0,row=9,sticky="nw",padx=30,pady=30,ipadx=20,ipady=10)

    def NOAA1():
        global NOAA
        NOAA = Toplevel(sat)
        NOAA.title("NOAA")
        NOAA.geometry("300x300")
        NOAA.config(bg="#0F0860")

        global NOAAme
        global NOAAme2
        NOAApop_label=Label(NOAA,text="The NOAA Satellite and Information Service \n provides timely access to global environmental \n data from satellites and other sources to monitor \n and understand our dynamic Earth",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        NOAAmy_frame= Frame(NOAA,bg="#0F0860")
        NOAAmy_frame.pack(pady=5)
        NOAAmep=Image.open(r"C:\python project\NOAA.jpg")
        NOAAmep=NOAAmep.resize((100,100),Image.ANTIALIAS)
        NOAAme=ImageTk.PhotoImage(NOAAmep)
        NOAAmep1=Image.open(r"C:\python project\NOAAqr.png")
        NOAAmep1=NOAAmep1.resize((100,100),Image.ANTIALIAS)
        NOAAme2=ImageTk.PhotoImage(NOAAmep1)
        NOAAl=Label(NOAAmy_frame,image=NOAAme)
        NOAAl.grid(row=0,column=0,padx=10)
        NOAAqr=Label(NOAAmy_frame,image=NOAAme2)
        NOAAqr.grid(row=1,column=0,padx=10)

        NOAAme_pic=Label(NOAAmy_frame,image=NOAAme)
        NOAAme_pic.grid(row=0,column=0,padx=10)
        NOAAme1_pic=Label(NOAAmy_frame,image=NOAAme2)
        NOAAme1_pic.grid(row=1,column=0,padx=10)
        q=Button(NOAAmy_frame, text="quit",command=NOAA.destroy)
        q.grid(row=0,column=2)


    NOAAmy_button=Button(Sframe,text="NOAA",command=NOAA1,bg="black",fg="#25B7F0",height=1,width=17)
    NOAAmy_button.grid(column=0,row=9,sticky="nw",padx=230,pady=30,ipadx=20,ipady=10)

    def galaxy1():
        global galaxy
        galaxy = Toplevel(sat)
        galaxy.title("galaxy")
        galaxy.geometry("300x300")
        galaxy.config(bg="#0F0860")

        global galaxyme
        global galaxyme2
        galaxypop_label=Label(galaxy,text="The Galaxy series is a family of communications \n satellites originally developed \n and operated by Hughes Communications.\n It has since merged with PanAmSat \n and is now owned and operated by Intelsat. ",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        galaxymy_frame= Frame(galaxy,bg="#0F0860")
        galaxymy_frame.pack(pady=5)
        galaxymep=Image.open(r"D:\spaceverse\galaxy satellite.jpg")
        galaxymep=galaxymep.resize((100,100),Image.ANTIALIAS)
        galaxyme=ImageTk.PhotoImage(galaxymep)
        galaxymep1=Image.open(r"D:\spaceverse\galaxysatqr.png")
        galaxymep1=galaxymep1.resize((100,100),Image.ANTIALIAS)
        galaxyme2=ImageTk.PhotoImage(galaxymep1)
        galaxyl=Label(galaxymy_frame,image=galaxyme)
        galaxyl.grid(row=0,column=0,padx=10)
        galaxyqr=Label(galaxymy_frame,image=galaxyme2)
        galaxyqr.grid(row=1,column=0,padx=10)

        galaxyme_pic=Label(galaxymy_frame,image=galaxyme)
        galaxyme_pic.grid(row=0,column=0,padx=10)
        galaxyme1_pic=Label(galaxymy_frame,image=galaxyme2)
        galaxyme1_pic.grid(row=1,column=0,padx=10)
        q=Button(galaxymy_frame, text="quit",command=galaxy.destroy)
        q.grid(row=0,column=2)


    galaxymy_button=Button(Sframe,text="GALAXY",command=galaxy1,bg="black",fg="#25B7F0",height=1,width=17)
    galaxymy_button.grid(column=0,row=10,sticky="nw",padx=30,pady=30,ipadx=20,ipady=10)

    def mangalyan1():
        global mangalyan
        mangalyan = Toplevel(sat)
        mangalyan.title("mangalyan")
        mangalyan.geometry("300x300")
        mangalyan.config(bg="#0F0860")

        global mangalyanme
        global mangalyanme2
        mangalyanpop_label=Label(mangalyan,text="The Mars Orbiter Mission (MOM), \n also called Mangalyaan (marscraft, from mangala, Mars and yāna, craft, vehicle), is a space probe orbiting Mars since 24 September 2014. It was launched on 5 November 2013 by the Indian Space Research Organisation (ISRO).",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        mangalyanmy_frame= Frame(mangalyan,bg="#0F0860")
        mangalyanmy_frame.pack(pady=5)
        mangalyanmep=Image.open(r"D:\spaceverse\Mangalyaan.jpg")
        mangalyanmep=mangalyanmep.resize((100,100),Image.ANTIALIAS)
        mangalyanme=ImageTk.PhotoImage(mangalyanmep)
        mangalyanmep1=Image.open(r"D:\spaceverse\mangalyaanqr.png")
        mangalyanmep1=mangalyanmep1.resize((100,100),Image.ANTIALIAS)
        mangalyanme2=ImageTk.PhotoImage(mangalyanmep1)
        mangalyanl=Label(mangalyanmy_frame,image=mangalyanme)
        mangalyanl.grid(row=0,column=0,padx=10)
        mangalyanqr=Label(mangalyanmy_frame,image=mangalyanme2)
        mangalyanqr.grid(row=1,column=0,padx=10)

        mangalyanme_pic=Label(mangalyanmy_frame,image=mangalyanme)
        mangalyanme_pic.grid(row=0,column=0,padx=10)
        mangalyanme1_pic=Label(mangalyanmy_frame,image=mangalyanme2)
        mangalyanme1_pic.grid(row=1,column=0,padx=10)
        q=Button(mangalyanmy_frame, text="quit",command=mangalyan.destroy)
        q.grid(row=0,column=2)


    mangalyanmy_button=Button(Sframe,text="MANGALYAAN(MOM)",command=mangalyan1,bg="black",fg="#25B7F0",height=1,width=17)
    mangalyanmy_button.grid(column=0,row=10,sticky="nw",padx=230,pady=30,ipadx=20,ipady=10)

    def insat1():
        global insat
        insat = Toplevel(sat)
        insat.title("insat")
        insat.geometry("300x300")
        insat.config(bg="#0F0860")

        global insatme
        global insatme2
        insatpop_label=Label(insat,text="INSAT or the Indian National Satellite System \n is a series of multipurpose Geo-stationary satellites \n launched by ISRO to satisfy the telecommunications, broadcasting,\n meteorology, and search and rescue needs of India.",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        insatmy_frame= Frame(insat,bg="#0F0860")
        insatmy_frame.pack(pady=5)
        insatmep=Image.open(r"D:\spaceverse\insat.jpg")
        insatmep=insatmep.resize((100,100),Image.ANTIALIAS)
        insatme=ImageTk.PhotoImage(insatmep)
        insatmep1=Image.open(r"D:\spaceverse\insatqr.png")
        insatmep1=insatmep1.resize((100,100),Image.ANTIALIAS)
        insatme2=ImageTk.PhotoImage(insatmep1)
        insatl=Label(insatmy_frame,image=insatme)
        insatl.grid(row=0,column=0,padx=10)
        insatqr=Label(insatmy_frame,image=insatme2)
        insatqr.grid(row=1,column=0,padx=10)

        insatme_pic=Label(insatmy_frame,image=insatme)
        insatme_pic.grid(row=0,column=0,padx=10)
        insatme1_pic=Label(insatmy_frame,image=insatme2)
        insatme1_pic.grid(row=1,column=0,padx=10)
        q=Button(insatmy_frame, text="quit",command=insat.destroy)
        q.grid(row=0,column=2)


    insatmy_button=Button(Sframe,text="INSAT",command=insat1,bg="black",fg="#25B7F0",height=1,width=17)
    insatmy_button.grid(column=0,row=11,sticky="nw",padx=30,pady=30,ipadx=20,ipady=10)

    def dawn1():
        global dawn
        dawn = Toplevel(sat)
        dawn.title("dawn")
        dawn.geometry("300x300")
        dawn.config(bg="#0F0860")

        global dawnme
        global dawnme2
        dawnpop_label=Label(dawn,text="Dawn is a retired space probe \n that was launched by NASA in September 2007 \n with the mission of studying two of \n the three known protoplanets \n of the asteroid belt: Vesta and Ceres.",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        dawnmy_frame= Frame(dawn,bg="#0F0860")
        dawnmy_frame.pack(pady=5)
        dawnmep=Image.open(r"D:\spaceverse\Dawn.jpg")
        dawnmep=dawnmep.resize((100,100),Image.ANTIALIAS)
        dawnme=ImageTk.PhotoImage(dawnmep)
        dawnmep1=Image.open(r"D:\spaceverse\dawnqr.png")
        dawnmep1=dawnmep1.resize((100,100),Image.ANTIALIAS)
        dawnme2=ImageTk.PhotoImage(dawnmep1)
        dawnl=Label(dawnmy_frame,image=dawnme)
        dawnl.grid(row=0,column=0,padx=10)
        dawnqr=Label(dawnmy_frame,image=dawnme2)
        dawnqr.grid(row=1,column=0,padx=10)

        dawnme_pic=Label(dawnmy_frame,image=dawnme)
        dawnme_pic.grid(row=0,column=0,padx=10)
        dawnme1_pic=Label(dawnmy_frame,image=dawnme2)
        dawnme1_pic.grid(row=1,column=0,padx=10)
        q=Button(dawnmy_frame, text="quit",command=dawn.destroy)
        q.grid(row=0,column=2)

    dawnmy_button=Button(Sframe,text="DAWN SPACE PROBE",command=dawn1,bg="black",fg="#25B7F0",height=1,width=17)
    dawnmy_button.grid(column=0,row=11,sticky="nw",padx=230,pady=30,ipadx=20,ipady=10)



    def stardust1():
        global stardust
        stardust = Toplevel(sat)
        stardust.title("stardust")
        stardust.geometry("300x300")
        stardust.config(bg="#0F0860")

        global stardustme
        global stardustme2
        stardustpop_label=Label(stardust,text="A 390-kilogram robotic space probe \n launched by NASA on 7 February 1999. \n Its primary mission was to collect dust samples\n  from the coma of comet Wild 2, as well as samples \n of cosmic dust, and return these \n to Earth for analysis.",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        stardustmy_frame= Frame(stardust,bg="#0F0860")
        stardustmy_frame.pack(pady=5)
        stardustmep=Image.open(r"D:\spaceverse\stardust.jpg")
        stardustmep=stardustmep.resize((100,100),Image.ANTIALIAS)
        stardustme=ImageTk.PhotoImage(stardustmep)
        stardustmep1=Image.open(r"D:\spaceverse\stardustqr.png")
        stardustmep1=stardustmep1.resize((100,100),Image.ANTIALIAS)
        stardustme2=ImageTk.PhotoImage(stardustmep1)
        stardustl=Label(stardustmy_frame,image=stardustme)
        stardustl.grid(row=0,column=0,padx=10)
        stardustqr=Label(stardustmy_frame,image=stardustme2)
        stardustqr.grid(row=1,column=0,padx=10)

        stardustme_pic=Label(stardustmy_frame,image=stardustme)
        stardustme_pic.grid(row=0,column=0,padx=10)
        stardustme1_pic=Label(stardustmy_frame,image=stardustme2)
        stardustme1_pic.grid(row=1,column=0,padx=10)
        q=Button(stardustmy_frame, text="quit",command=stardust.destroy)
        q.grid(row=0,column=2)


    stardustmy_button=Button(Sframe,text="STARDUST",command=stardust1,bg="black",fg="#25B7F0",height=1,width=17)
    stardustmy_button.grid(column=0,row=12,sticky="nw",padx=30,pady=30,ipadx=20,ipady=10)

    def rex1():
        global rex
        rex = Toplevel(sat)
        rex.title("rex")
        rex.geometry("300x300")
        rex.config(bg="#0F0860")

        global rexme
        global rexme2
        rexpop_label=Label(rex,text="OSIRIS-REx (Origins, Spectral Interpretation,\n Resource Identification, Security, Regolith Explorer) \n is a NASA asteroid-study and sample-return mission. \n The mission's primary goal is to obtain a sample \n of at least 60 g (2.1 oz) from 101955 Bennu,\n a carbonaceous near-Earth asteroid, \n and return the sample to Earth for a \n detailed analysis.",bg="#0F0860",fg="white", font=("helvetica",12)).pack()
        rexmy_frame= Frame(rex,bg="#0F0860")
        rexmy_frame.pack(pady=5)
        rexmep=Image.open(r"D:\spaceverse\osiris.jpg")
        rexmep=rexmep.resize((100,100),Image.ANTIALIAS)
        rexme=ImageTk.PhotoImage(rexmep)
        rexmep1=Image.open(r"D:\spaceverse\rexqr.png")
        rexmep1=rexmep1.resize((100,100),Image.ANTIALIAS)
        rexme2=ImageTk.PhotoImage(rexmep1)
        rexl=Label(rexmy_frame,image=rexme)
        rexl.grid(row=0,column=0,padx=10)
        rexqr=Label(rexmy_frame,image=rexme2)
        rexqr.grid(row=1,column=0,padx=10)

        rexme_pic=Label(rexmy_frame,image=rexme)
        rexme_pic.grid(row=0,column=0,padx=10)
        rexme1_pic=Label(rexmy_frame,image=rexme2)
        rexme1_pic.grid(row=1,column=0,padx=10)
        q=Button(rexmy_frame, text="quit",command=rex.destroy)
        q.grid(row=0,column=2)


    rexmy_button=Button(Sframe,text="OSIRIS-REX",command=rex1,bg="black",fg="#25B7F0",height=1,width=17)
    rexmy_button.grid(column=0,row=12,sticky="nw",padx=230,pady=30,ipadx=20,ipady=10)


    satbut=Button(Sframe,text="<---GO BACK TO TARDIS",bg="#195267",fg="#F0BE25",command=tardsat)
    satbut.grid(column=0,row=0,sticky="nw",pady=10,padx=25)
    ef=Button(Sframe,text="END THE JOURNEY--->",command=exisat ,bg="#195267",fg="#F0BE25")
    ef.grid(column=0,row=0,sticky="nw",pady=10,padx=270)
    sat.mainloop()
# sat1()


def tardsp():
    space.destroy()
    tard()

def tardsat():
    sat.destroy()
    tard()


'''*****************************************************'''
def tard():
    global tardis
    tardis= Tk()
    tardis.title('SPACEVERSE 2.0')
    tardis.geometry("800x500")
    tardis.configure(bg="black")
    rootim=Image.open(r"D:\spaceverse\all.png")
    rootim2=rootim.resize((800,500),Image.ANTIALIAS)
    rootiml=ImageTk.PhotoImage(rootim2)
    tlabel=Label(image=rootiml)
    tlabel.place(x=0,y=0)
    text1=Label(tardis,text="SPACE-VERSE 2.0",fg="#F0BE25",bg="#202F4D",font="helvetica 17 underline").place(rely = 0.01,relx=0.4)
    text1=Label(tardis,text="'All of time\n And Space Everywhere \n and Anywhere,Every Star that ever Was....\n Where Do You Want To Start?...' \n \n                  - Doctor  Who",fg="#F0BE25",bg="#202F4D",font=("helvetica",13)).place(rely = 0.2,relx=0.54)
    enterbut=Button(tardis,text="SPACE",command=tarddestroy,bg="black",fg="#25B7F0")
    enterbut.place(rely = 0.2,relx=0.5)
    enterbut=Button(tardis,text="SATELLITES",command=satdestroy,bg="black",fg="#25B7F0")
    enterbut.place(rely = 0.7,relx=0.5)
    ef=Button(tardis,text="END THE JOURNEY",command=exitard ,bg="#195267",fg="#F0BE25")
    ef.place(rely =0.8,relx=0.7)
    tardis.mainloop()

'''***********************************************'''
tard()

