# Demo public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            ServiceReference1.Service1Client c = new ServiceReference1.Service1Client();
            
            label1.Text = c.GetData(1);
        }

        private void label1_Click(object sender, EventArgs e)
        {

        }
    }
